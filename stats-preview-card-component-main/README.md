# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot
Desktop:

![](./Solution%20-%20dekstop.png)

Mobile:

![](./Solution%20-%20mobile.png)

### Links

- Live Site URL: [Netlify](https://fabulous-dragon-7a0b3e.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- CSS Media

### What I learned

I learned a lot about responsiveness for different screen widths. Had an opportunity to practice flex and grid layouts. I had big problem changing the image background to violet but eventually figured it out

To make an image overlay with color:

```html
  <div class="card-img">
    <div class="img-overlay"></div>
  </div>
```
```css
.card-img {
    width: 50%;
    background: url("./images/image-header-desktop.jpg");
}

.img-overlay {
    width: 100%;
    height: 100%;
    background-color: rgba(113, 2, 165, 0.582);
}
```

## Author

- Frontend Mentor - [@piotpel](https://www.frontendmentor.io/profile/piotpel)