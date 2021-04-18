# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

[![Netlify Status](https://api.netlify.com/api/v1/badges/88ce352e-8d9a-4cfe-a14c-47d58f23bc0e/deploy-status)](https://app.netlify.com/sites/jolly-yonath-78d966/deploys)

## Table of contents

- [Frontend Mentor - Stats preview card component solution](#frontend-mentor---stats-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](src/img/desktop.png)
![](src/img/mobile.png)

### Links

- Solution URL: [https://github.com/miguel-tostado/stats-preview-card-component](https://github.com/miguel-tostado/stats-preview-card-component)
- Live Site URL: [https://jolly-yonath-78d966.netlify.app/](https://jolly-yonath-78d966.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

This project introduced me to the css blend properties, specifically mix-blend-mode. Wasn't too difficult to figure out; however, getting the screenshot to work properly on Frontend Mentor's website was proving to be difficult. Each time I uploaded I only saw a color background without an image on the screenshot despite everything working properly on a live site. Thankfully, I found an article that went over the isolation css property.

```css
.img-color-wrap {
  background-color: var(--color-soft-violet);
  isolation: isolate;
}

.image-div {
  background-position: center;
  background-repeat: no-repeat;
  background-size: contain;
  mix-blend-mode: multiply;
  opacity: 0.75;
}
```

### Useful resources

- [How to use CSS blend modes](https://getflywheel.com/layout/css-blend-modes/) - This helped with the blend properties and taught me the isolation css property.

## Author

- Website - [Miguel Tostado](https://www.migueltostado.com/)
- Frontend Mentor - [@miguel-tostado](https://www.frontendmentor.io/profile/miguel-tostado)
- Twitter - [@207Toast](https://twitter.com/207Toast)