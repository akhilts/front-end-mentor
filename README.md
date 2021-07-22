# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot.JPG)


### Links

- Solution URL: [Solution](https://your-solution-url.com)
- Live Site URL: [front-end-mentor](https://akhilts.github.io/front-end-mentor/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

```html 
picture tags comes handy for responsive image changes
<picture>
  <source media="(min-width:650px)" srcset="img_pink_flowers.jpg">
  <source media="(min-width:465px)" srcset="img_white_flower.jpg">
  <img src="img_orange_flowers.jpg" alt="Flowers" style="width:auto;">
</picture>

```
```css

Use of media tags for responsive design 

@media screen and (max-width: 1080px){
    .container{
        flex-direction: column;
        padding:8vw;
    }
```

### Continued development

Some areas I need to work moving forward

- CSS Grid Layout and <center> tag
- Grid Layout vs Flex Box
- Working with images in responsive design
- Mobile-first workflow

### Useful resources

- (https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Amazing guide on CSS Flex Box
  I'd recommend it to anyone still learning this concept.

## Author

- LinkedIn - [Akhil T S](https://www.linkedin.com/in/akhilts2204/)
- Frontend Mentor - [@akhilts](https://www.frontendmentor.io/profile/akhilts)
- Twitter - [@akhilts](https://www.twitter.com/akhilts)

## Acknowledgments

I would lke to extend my sincere thanks to Kevin Powell who suggested this amazing platform for sharpening frontend skills.
