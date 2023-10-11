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


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![desktop preview image](design/desktop-design.jpg)

![mobile preview image ](design/mobile-design.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [See Live](https://stackritesh.me/frontendmentor-challenges/stats-preview-card-component-main/index.html)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

The image has a purple overlay like effect which you can create using `mix-blend-mode` the color in the image container is a solid color when we multiply the background with the image it creates this overlay like effect. 

```html
<div class="wrapper wrapper__img">
  <img class="desktop-img" src="images/image-header-desktop.jpg" alt="desktop image">
</div>
```

```css
.wrapper__img {
    width:100%;
    background: hsl(277, 64%, 61%);
}

img {
    display: block;
    max-width: 100%;
    mix-blend-mode: multiply;
}
```

## Author

- Frontend Mentor - [@git-ritesh](https://www.frontendmentor.io/profile/git-ritesh)
- Twitter - [@sanatanispirit](https://www.twitter.com/sanatanispirit)
