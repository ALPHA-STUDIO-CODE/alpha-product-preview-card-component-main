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
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Media Queries

### What I learned

```html
<picture>
  <source
    media="(min-width: 900px)"
    srcset="./assets/images/image-product-desktop.jpg"
  />
  <img
    src="./assets/images/image-product-mobile.jpg"
    id="image"
    alt="Perfume jpg"
  />
</picture>
```

```css
#big {
  margin: 15% auto 0.714rem auto;
  width: 95%;
  border-radius: 0.714rem;
  background: hsl(0, 0%, 100%);
}
```

## Author

- Frontend Mentor - [@ALPHA-STUDIO-CODE](https://www.frontendmentor.io/profile/ALPHA-STUDIO-CODE)
- Twitter - [@ALPHASTUDIOCODE](https://x.com/ALPHASTUDIOCODE)

## Acknowledgments

Thanks to Frontend Mentor for giving us this place to learn, train, and grow. Thanks also to W3Schools for their in-depth documentation and to Overflow for bringing developers together to work on problems.
