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
- CSS
- Flexbox
- Google Fonts (Young Serif, Outfit)
- `::marker` for list styling

### What I learned

- Using `::marker` makes it easy to style list bullets and numbering without extra markup.
- `border-collapse` helps create clean, simple table dividers without double borders.
- Pairing `100vh` with `100svh` improves vertical centering on mobile browsers.

### Continued development

- Refine responsive typography with `clamp()` for smoother scaling.
- Add focus styles for links to improve keyboard accessibility.
- Experiment with CSS custom properties to make theme changes faster.

### Useful resources

- [MDN: ::marker](https://developer.mozilla.org/en-US/docs/Web/CSS/::marker) - Clear examples for styling list markers.
- [MDN: border-collapse](https://developer.mozilla.org/en-US/docs/Web/CSS/border-collapse) - Helped clean up the table borders.
- [MDN: min-height](https://developer.mozilla.org/en-US/docs/Web/CSS/min-height) - Useful for responsive layout decisions.

### AI Collaboration

- Used Codex to troubleshoot CSS spacing, list styling, and table borders.
- Asked for quick explanations of layout choices (flex vs. grid) to confirm best practices.

## Author

- Frontend Mentor - [@BOYWIDASTEEZ](https://www.frontendmentor.io/profile/BOYWIDASTEEZ)

