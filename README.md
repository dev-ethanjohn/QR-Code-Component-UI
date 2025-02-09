# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help me improve my coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

### Desktop Version

![Desktop Version](/images/desktop-view.png)

### Mobile Version

![Mobile Version](/images/mobile-view.png)

### Links

- Solution URL: [https://github.com/dev-ethanjohn/QR-Code-Component-UI.git](https://github.com/dev-ethanjohn/QR-Code-Component-UI.git)
- Live Site URL: [https://qr-code-component-ui.vercel.app/](https://qr-code-component-ui.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I got to learn about CSS flexbox and alignment properties. Structuring my HTML although not yet really optimized.

In this project Im using a fixed width based off from the fixed dimension of the card design from Figma. I found adding padding to the parent container is unnecessary with flexbox (center) unless I want to have explicit horizontal padding in smaller devices and the card itself has adaptable width dimension.

### Continued development

My goal is to have more in depth knowledge and practice using flexbox and grid -> next. Semantic tags and standard way to structure different html elements. When to use divs, semantic tags, correct naming of classes. etc.

### Useful resources

- [CSS selector and inheritance](https://forum.freecodecamp.org/t/universal-selector-and-body-selector-rules/425144) - The discussion helped me intuitively select which selectors to apply and what default properties I need to put in order to have consistent style.

For example:

```CSS
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
} // This prevents inconsistent spacing across browsers
```

## Author

- Frontend Mentor - [@dev-ethanjohn](https://www.frontendmentor.io/profile/dev-ethanjohn)
- Instagram - [@dev.ejohn](https://www.instagram.com/dev.ejohn/)
