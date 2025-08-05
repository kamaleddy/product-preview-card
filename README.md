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

![](./screenshot/Desktop%20View.png)
![](./screenshot/Mobile%20View.png)

### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa)
- Live Site URL: [Add live site URL here](https://kamaleddy.github.io/product-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Google Fonts
- Flexbox
- Mobile-first workflow

### What I learned

Learn how to use the <picture> element to serve different images on different screen sizes.

```html
<picture class="product-image">
  <source
    srcset="./images/image-product-desktop.jpg"
    media="(min-width: 675px)"
  />
  <img src="./images/image-product-mobile.jpg" alt="Perfume of Gabrielle" />
</picture>
```

### Continued development

Learning how add a button to allow users to choose how many items to add to the cart and learn how to store the product in a cart object and show a simple cart summary somewhere on the page. .

### Useful resources

- [picture element](https://web.dev/learn/design/picture-element) - This helped me understand more about picture element and how to use it and apply to the project.

## Author

- Github - [@kamaleddy](https://github.com/kamaleddy)
- Frontend Mentor - [@kamaleddy](https://www.frontendmentor.io/profile/kamaleddy)
