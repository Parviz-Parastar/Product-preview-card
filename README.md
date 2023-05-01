# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

#### Screenshot desktop:
  ![]screenshot-desktop](https://github.com/Parviz-Parastar/Product-preview-card/blob/main/screenshot/desktop.png?raw=true)

***
  ![]screenshot-mobile](https://github.com/Parviz-Parastar/Product-preview-card/blob/main/screenshot/mobile.png?raw=true)

### Links

- Solution URL: [Add solution URL here](https://github.com/Parviz-Parastar/Product-preview-card)
- Live Site URL: [Add live site URL here](https://parviz-parastar.github.io/Product-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Thanks to CSS3, I was able to learn to work with transitions, transforms and animations and source tag in HTML and give interesting movement modes to the elements.

To see how you can add code snippets, see below:

```html
 <source media="(min-width: 700px)" srcset="images/image-product-desktop.jpg">

```css
main,
body {
    transform: scale(1);
    animation: 1.5s ease;
}

@-webkit-keyframes Entry-from-above {
    0% {
        -webkit-transform: scale(0.1);
        transform: scale(0.1);
        filter: saturate(0.1);
        position: absolute;
        opacity: 1;
        top: -50vh;
        left: 50vh;
        right: 50vh;
    }

    50% {
        -webkit-transform: scale(0.5);
        transform: scale(0.5);
        filter: saturate(0.5);
        position: absolute;
        opacity: 1;
        top: 10vh;
        left: 50vh;
        right: 50vh;
    }

    100% {
        -webkit-transform: scale(1);
        transform: scale(1);
        filter: saturate(1);
    }

### Continued development

I want to learn css3 elements better.

## Author
  I am very grateful to the management of the frontend mentor site and the active users on this site.
