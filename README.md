# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Stats preview card component solution](#frontend-mentor---stats-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

<p align="center">
  <img src="design/desktop-view.png">
  <br>Desktop View
</p>

<p align="center">
  <img src="design/mobile-view.png">
  <br>Mobile View
</p>

- Solution URL: [Github](https://github.com/akashdeepnandi/frontend-mentor-card-component)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS variables
- Flexbox
- CSS Grid
- Mobile-first workflow
- CSS media queries
- [Vite.js for project scaffolding](https://vitejs.dev/)

### What I learned

When I was developing this, the most annoying issue I faced while trying to overlay the color on the image.

<p align="center">
  <img src="design/problem.png">
  <br>Extra padding inside the .card-image div shown with borders
</p>

Yes, this annoying little extra margin of 3px. But thankfully I found an wonderful solution from a thoroughly explained answer in [here](https://stackoverflow.com/questions/5804256/image-inside-div-has-extra-space-below-the-image).

So the fix was simple, to convert image into a display of block.

```css
.card-image img {
  ...
  display: block;
  ...
}
```

### Continued development

CSS can definitely have some refactoring, maybe using SCSS but I think it will be an overkill for such an simple component

### Useful resources

- [W3Schools](https://www.w3schools.com/) - For reference of html tag attributes and css properties.

## Author

- Website - [Akashdeep Nandi](https://github.com/akashdeepnandi)
- Frontend Mentor - [@akashdeepnandi](https://www.frontendmentor.io/profile/akashdeepnandi)
