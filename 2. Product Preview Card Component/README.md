# Frontend Mentor - Product Preview Card Component

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

## Table of Contents

- [Overview](#overview)
  - [Features](#features)
  - [Screenshots](#screenshots)
- [My Process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Features
- Responsive design which creates optimal layouts depending on the viewport width
- Interactive elements with hover-over effects

### Screenshots
- Desktop version  
![](./images/screenshot-desktop.jpg)

- Mobile version  
![](./images/screenshot-mobile.jpg)

## My Process

### Built with
- HTML5: semantic markups
- CSS3: box model, flexbox, media query, pseudo-class, transition

### What I learned
- Using `CSS Media Query` to make webpages responsive to the viewport width
    
  ```
  @media (max-width: 540px) {
    .card {
        flex-flow: column wrap;
        max-width: 95vw;
    }

    #image-product-desktop {
        display: none;
    }

    #image-product-mobile {
        width: 95vw;
        border-radius: 10px 10px 0 0;
    }
  }
- Using `CSS Flexbox` properties to position items in a flex container
- Styling elements with smooth hover-over effects using `CSS Pseudo-class` selector and `CSS Transition` property

### Continued development
- Mobile-first workflow: For this project, I started with the desktop version and then scaled it down to make the mobile version. Towards the end of the project, I came across the mobile-first concept. It was too late to implement it into this project, but I want to start implementing it in future project development.
- CSS media query: It is the first project for me to practice CSS media query. I used [W3Schools](https://www.w3schools.com/) and [MDN Web Docs](https://developer.mozilla.org/en-US/) to guide me through. I want to familiarize myself with this feature and be able to code it efficiently.

### Useful resources
- Using media queries: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries

## Author

- Website - N/A
- GitHub - [@code-sparkle](https://github.com/code-sparkle)
- Frontend Mentor - [@code-sparkle](https://www.frontendmentor.io/profile/code-sparkle)

## Acknowledgments
