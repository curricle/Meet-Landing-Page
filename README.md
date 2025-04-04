# Frontend Mentor - Meet landing page solution

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](assets/screenshot.png)

### Links

- Solution URL: [Solution on Frontend Mentor](https://www.frontendmentor.io/solutions/meet-landing-page-using-scss-L7Pe0dgBSR)
- Live Site URL: [GitHub Pages](https://curricle.github.io/Meet-Landing-Page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- [SCSS](https://sass-lang.com/)

### What I learned

I re-familiarized myself with SCSS for this project. Some new concepts I explored were extending SCSS classes, though I'll need more practice to become familiar with when to use extends vs when to use mixins. Additionally, I used the built-in `sass:color` and `sass:math` modules which I've never used before.

I also used the `clamp()` function for the first time. Once again I'll need more practice to really nail the usage and which values are most appropriate.

Additionally I learned about the `<picture>` tag for swapping out images according to screen size without having to set background images for empty HTML elements.

### Useful resources

- [Sass Documentation: @extend](https://sass-lang.com/documentation/at-rules/extend/) - This helped me with creating reusable text styles.
- [Sass Documentation: Built-in Modules](https://sass-lang.com/documentation/modules/) - Documentation for Sass's built-in modules (including `sass:color` and `sass:math`).
- [Modern Fluid Typography: CSS Clamp](https://www.smashingmagazine.com/2022/01/modern-fluid-typography-css-clamp/) - This is the resource I used to better understand what the `clamp()` function does and how to use it.
- [<picture> at W3 Schools](https://www.w3schools.com/tags/tag_picture.asp) - Info about the `<picture>` tag, which can the image out according to screen size. Did not know that was a thing before!
- [How to Overlay Your Background Images](https://dev.to/selbekk/how-to-overlay-your-background-images-59le) - For the footer background overlay, though I think the more "correct" solution would have been to use CSS grid and the `<picture>` tag.

## Author

- Website - [Steph Jordan](https://jordanmakes.com)
- Frontend Mentor - [@curricle](https://www.frontendmentor.io/profile/curricle)

## Acknowledgments

Thanks to [Professora Bianca](https://www.frontendmentor.io/profile/ProfessoraBianca) for informing me about `clamp()` in the comments of my last project.
