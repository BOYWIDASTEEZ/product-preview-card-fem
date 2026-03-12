# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
- [The challenge](#the-challenge)
- [Links](#links)
- [My process](#my-process)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Continued development](#continued-development)
- [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the recipe page on both desktop and mobile screens.
- Read the content clearly with distinct sections for preparation, ingredients, instructions, and nutrition.

### Links

- Solution URL: ('https://github.com/BOYWIDASTEEZ/product-preview-card-fem.git')
- Live Site URL: ('https://recipe-main-page-fem.vercel.app/)

## My process

- Built a two-column card layout with `display: flex` so the image and content sit side-by-side on desktop.
- Set a fixed card width and rounded corners, then used `overflow: hidden` to keep the image clipped cleanly.
- Applied `object-fit: cover` so the product image fills its area without distortion.
- Used the style guide fonts: **Fraunces** for headings and **Montserrat** for body text and UI.
- Created a price row with flex alignment and spacing for clear visual hierarchy.
- Styled the CTA as a full-width button with icon + text and hover feedback.
- Added a mobile breakpoint to stack the image above the content for small screens.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Responsive layout with media queries
- Google Fonts (Fraunces, Montserrat)

### What I learned

- A small breakpoint change can make a big difference for mobile layout and readability.

### Continued development

- Swap in the mobile product image at small breakpoints.
- Improve accessibility with visible focus styles and better contrast checks.
- Refine typography scaling using `clamp()` for smoother responsiveness.

### Useful resource

- [Google Fonts](https://fonts.google.com/) - Used to load Fraunces and Montserrat.

## Author

- Frontend Mentor - [@BOYWIDASTEEZ](https://www.frontendmentor.io/profile/BOYWIDASTEEZ)
