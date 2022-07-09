# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### Screenshot

![Desktop](https://github.com/owtwo/QRCode_Component/blob/main/img/qr-code-component-screenshot.jpeg)

### Links

- Solution URL: [View solution](https://github.com/owtwo/QRCode_Component)
- Live Site URL: [View live site](https://owtwo.github.io/QRCode_Component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

This project helped me get more comfortable with Flexbox. Flexbox works on the direct child of a parent element not the other descendants. For example in the code below Flebox only targeted the div element and not the other elements contained in the div.
```html
<body>
    <div class="container">
        <img class="qr-img" src="img\image-qr-code.png" alt="QR code">
        <h1 class="bold-caption">Improve your front-end skills by building projects</h1>
        <p class="regular-caption">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    </div>
</body>
```
Also got to understand in detail how margins and paddings help to position and style elements. For example the code below can be used to center an element.
```css
.container {
 margin: 0 auto;
}
``` 
Variables came in handy to reduce the number of changes I had to make if I didn't like a particular color. For instance in the code below all colors used in the project are declared as variables.
```css
:root {
    --white: hsl(0, 0%, 100%);
    --lightgray: hsl(212, 45%, 89%);
    --grayishblue: hsl(220, 15%, 55%);
    --darkblue: hsl(218, 44%, 22%);
}
```
### Useful resources

- [Centering CSS a complete guide](https://css-tricks.com/centering-css-complete-guide/) - This is a great article which helped me finally understand the various ways to center elements on a webpage. It also goes into the scenarios for which each method works best. I'd recommend it to anyone still learning this concept.

## Author

- Frontend Mentor - [@owtwo](https://www.frontendmentor.io/profile/owtwo)




