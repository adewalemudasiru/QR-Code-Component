# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

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
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

Desktop Screenshot
![Desktop Screenshot](./screenshots/qrcode%20desktop.jpeg)
Mobile Screenshot <br />
![Mobile Screenshot](./screenshots/qrcode%20mobile.jpeg)

### Links

- Solution URL: [Github](https://github.com/adewalemudasiru/QR-Code-Component)
- Live Site URL: [SolutionPreview](https://your-live-site-url.com)

## My process

I created a section and assigned a class value "wrapper" to it. I then created a div (class="container") inside the wrapper to house all the content of the qr code component. Using CSS flexbox, I aligned the wrapper horignally and vertically to the center of the screen. I changed the image to a block element so I can easily align it to the center and gave the container a uniform padding of 15px. To get the title and description to match or close to the original desgin, I had to use right left padding of 15px.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

I learned how to add shadows to elements using the `box-shadow` CSS property.

```html
<div class="box shadow">🎉</div>
```
```css
.box {
  width: 100px;
  height: 100px;
  color: blue:
}

.shadow {
  box-shadow: 0px 0px 10px 5px blue;
}
```

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Javascript is proving to be my greatest nightmare and I'm going to keep learning it. I want to also improve on my css skills and learn how to use the calc function and more ways to use flexbox and grid.

### Useful resources

- [ChatGPT](https://openai.com/chatgpt/) - I used chatgpt to figure out how to add shadows to an element.

## Author

- Website - [Adewale Mudasiru](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/adewalemudasiru)
- Twitter - [@ade_mudasiru](https://www.twitter.com/ade_mudasiru)

## Acknowledgments

ChatGPT helped me figure out how to add shadows to an element.