# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/YohannDCz/MusicalCard/blob/main/index.html)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<svg class="image1" xmlns="http://www.w3.org/2000/svg" width="1440" height="437"><path fill="#D6E1FF" fill-rule="evenodd" d="M0 349.974c218.558 116.035 460.05 116.035 724.475 0s502.933-116.035 715.525 0V0H0v349.974z"/></svg>
  <svg class="image2" xmlns="http://www.w3.org/2000/svg" width="1440" height="437"><path fill="#D6E1FF" fill-rule="evenodd" d="M0 349.974c218.558 116.035 460.05 116.035 724.475 0s502.933-116.035 715.525 0V0H0v349.974z"/></svg>
  <svg class="image3" xmlns="http://www.w3.org/2000/svg" width="1440" height="437"><path fill="#D6E1FF" fill-rule="evenodd" d="M0 349.974c218.558 116.035 460.05 116.035 724.475 0s502.933-116.035 715.525 0V0H0v349.974z"/></svg>
```
```css
.image1 {
    position: absolute;
    top: 0;
    right: 0;
    left: 0;
    width: 100%;
    object-fit: contain;
    z-index: -1;
}

.image2 {
    position: absolute;
    right: 0;
    left: 0;
    width: 100%;
    align-content: baseline;
    height: 496px;
    object-fit: cover;
    transform: scaleX(-1) scaleY(-1);
    z-index: 0;
    filter: drop-shadow( 4px 4px 30px rgba(182, 199, 255, 0.713));
}

.image3 {
    position: absolute;
    right: 0;
    left: 0;
    bottom: 0;
    width: 100%;
    transform: scaleX(-1) scaleY(-1);
}
```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/YohannDCz)
