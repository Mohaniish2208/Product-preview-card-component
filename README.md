# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Workflow](#workflow)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Desktop view](Desktop-view(without-mouse-hover).png) 
![Desktop view](Desktop-view(with-mouse-hover).png)

### Links

- Solution URL: [Solution](https://github.com/Mohaniish2208/Product-preview-card-component.git)
- Live Site URL: [Live site](https://mohaniish2208.github.io/Product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Sass
- Custom CSS (Desktop-first)
- CSS Flexbox for layout
- Responsive design using media queries
- Google Fonts (`Fraunces`, `Montserrat`)
- Material Symbols for cart icon (🛒)

### Workflow

### What I learned

- I learned how to implement `letter-spacing` to control the spacing between characters for a more polished look.
- I discovered how using `&:hover` in CSS is actually SCSS syntax — not valid in pure CSS unless using a preprocessor like Sass.
- I’ve started **compartmentalizing my HTML** using clear comment sections (e.g., `<!-- CSS docs -->`, `<!-- Fonts -->`) to keep my codebase organized and readable.
- I practiced making designs responsive and accessible by matching layout and typography across screen sizes as instructed in the challenge brief.

```html
 
  <!-- CSS docs -->
  <link href = "mobile.css" rel = "stylesheet">
  <link href = "desktop.css" rel = "stylesheet">
  
  <!-- Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&family=Outfit:wght@100..900&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,100..900;1,9..144,100..900&family=Montserrat:ital,wght@0,100..900;1,100..900&family=Outfit:wght@100..900&display=swap" rel="stylesheet">
  
  <!-- Symbols -->
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200&icon_names=shopping_cart" />

```
This is something I have started to pay attention to: compartmentalizing my code using clear comment sections like <!-- CSS docs -->, <!-- Fonts -->, and <!-- Symbols --> to keep my HTML more organized and readable.

```css
.btn{
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 0.7em;
    background-color: hsl(158, 36%, 37%);
    border-radius: 0.5em;
    color: hsl(0, 0%, 100%);
    gap: 0.5em;
    &:hover{
        cursor: pointer;
        background-color: hsl(158, 42%, 18%);
        transition: 1s ease-in-out;
    }
}
```
This is something new I learned in this project: how to use &:hover inside a CSS rule to apply hover effects cleanly, which is part of SCSS syntax rather than plain CSS.

### Continued development

In future projects, I want to:

- Convert this layout into a React component using Styled Components.

- Make it accessible with keyboard navigation and improved ARIA roles.

- Animate the card or button using CSS transitions or keyframes.

### Useful resources

- [Google Fonts](https://fonts.google.com/?selected=Material+Symbols+Outlined:shopping_cart:FILL@0;wght@400;GRAD@0;opsz@24&icon.set=Material+Symbols&icon.size=24&icon.color=%231f1f1f) - This helped me for importing fonts.

- [Material Symbols](https://fonts.google.com/icons?selected=Material+Symbols+Outlined:shopping_cart:FILL@0;wght@0;GRAD@0;opsz@24&icon.size=24&icon.color=%231f1f1f) - This helped me embed the "Shopping Cart" symbol.
README.md
## Author

- GitHub - [@Mohaniish2208](https://github.com/Mohaniish2208)

- Frontend Mentor - [@Mohaniish2208](https://www.frontendmentor.io/profile/Mohaniish2208)

## Acknowledgments

I would like to thank Frontend Mentor for providing this challenge — it helped me practice responsive layout, spacing, and clean CSS structure. Special appreciation to the Frontend Mentor community, whose solutions and feedback offer continuous learning and inspiration.

Also, thanks to Google Fonts and Material Symbols for their free and easy-to-integrate resources that enhanced the visual appeal of this project.