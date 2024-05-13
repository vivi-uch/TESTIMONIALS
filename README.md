# Frontend Mentor - Testimonials grid section solution

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Links

- Solution URL: (https://vivi-uch.github.io/TESTIMONIALS/)
- Live Site URL: (https://github.com/vivi-uch/TESTIMONIALS)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Responsive Layouts

### What I learned

```css
.box1 .quote-img{
    position: relative;
    /* display: none; */
    left: 190px;
    top: -70px;
}
.box1 .overlay-text{
  position: relative;
  top: -120px;
}
.container .box3{
  grid-row: span 2;
  height: auto;
}
.container{
  display: grid;
  grid-template-columns: 1fr auto;
  grid-template-rows: 1fr auto;
  gap: 12px;
}
```

### Useful resources

- [Frontend Mentor](https://www.frontendmentor.io/home)
- [Udemy Angela Yu Web dev course](https://www.udemy.com/course/the-complete-web-development-bootcamp/)
- [ChatGPT](https://chat.openai.com/) 
- [W3school](https://www.w3schools.com/) 

## Author

- Linkeldn - [vivian okonkwo](https://www.linkedin.com/in/vivian-okonkwo-24b228253/)
- Frontend Mentor - [@okonks](https://www.frontendmentor.io/profile/okonks)


