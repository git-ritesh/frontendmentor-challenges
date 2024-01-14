# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the site depending on their device's screen size

### Screenshot
**Desktop Design**

![Desktop Design](design/desktop-design.jpg)

<p align="right"><b>Mobile Design</b></p>
<img align="right" width="300px" src="design/mobile-design.jpg" alt="mobile design image">


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [visit](https://git-ritesh.github.io/frontendmentor-challenges/testimonials-grid-section-main/index.html)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned
- used `clamp` function to create a changing background position for the background image. Below code snippet applies to the element in which the background is present. 

  ```css
  .item1 {
    background : color url(./images/quote.png) no-repeat top right clamp(1.5rem, 6vw, 5rem); 
  }
  ```
  Above code inserts the quote icon in the background and puts it to at 0px from the top & (24px --> 80px) from the right side.

- Grid is very useful for creating complex & rigid layouts.

### Continued development

I'm going to dive more deep about Grid Auto Flow & some functions like `minmax` which are used with grid.

## Author

- Website - [stackritesh.me](https://www.stackritesh.me/)
- Frontend Mentor - [@git-ritesh](https://www.frontendmentor.io/profile/git-ritesh)
- Twitter - [@shadowlurk3r](https://www.twitter.com/shadowlurk3r)
