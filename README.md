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
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

### Mobile Version
![](/images/product-card-mobile.png)

### Desktop Version
![](/images/product-card-desktop.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [dz-product-preview-card-component](https://dz-product-preview-card-component.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- CSS Logical Properties
- BEM

### What I learned

In this challenge, I learned how to work with fluid space and how to build a responsive grid layout without using media queries. I also revisited how I used custom properties, this time I used only primitives without tokens to keep it easier to maintain, but for the next challenge, I'll combine primitives and tokens with this approach.

```css
.proud-of-this-css {
  /* Single column on small device become two columns layout on large device */
  grid-template-columns: repeat(auto-fit, minmax( 18rem, 1fr));

  /* Fluid margin 1rem on small device growing up to 1.5rem on large device */
  margin-block-start: clamp(1rem, 0.8239rem + 0.7512vw, 1.5rem);
}
```

### Continued development

While awaiting JavaScript challenges, I'll be focused on CSS Grid, Flexbox, Fluid typography, Fluid spacing, Custom properties and how to build responsive layouts without using media queries.

### Useful resources

- [Responsive grid](https://travishorn.com/responsive-grid-in-2-minutes-with-css-grid-layout-4842a41420fe) - Short article about responsive grid layout.

- [Responsive grid](https://gomakethings.com/how-to-create-a-responsive-grid-system-with-css-grid/) - Another article on how to create responsive grid layout.

- [Responsive grid](https://css-tricks.com/look-ma-no-media-queries-responsive-layouts-using-css-grid/) - Last usefull article on how to make responsive grid layout without using media queries.

- [How to make responsive image](https://dev.to/dostonnabotov/the-html-element-explained-48o8) - In this article we can understand how to use `<picture>` to display images based on screen device.

- [CSS Reset by Andy Bell](https://piccalil.li/blog/a-more-modern-css-reset/) - One of the best CSS around the web.

## Author

- Frontend Mentor - [@dedo-dev](https://www.frontendmentor.io/profile/dedo-dev)
- Linkedin - [@daniele-zeppieri](https://www.linkedin.com/in/daniele-zeppieri-0b1a36252/)