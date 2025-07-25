# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### Screenshot

![Solution preview for the Recipe page coding challenge](./recipe%20solution.jpeg)

### Links

- Solution URL: [Github repo](https://github.com/DrewM64/recipe-page)
- Live Site URL: [Github Pages URL](https://drewm64.github.io/recipe-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This was the first time in a long time that I used media queries. I am happy with how it turned out, although I had noticed some bugs when it came to resizing the page. Because I was initially developing the page at 375px wide, I hadn't set a width for the `.main-desktop` element. This caused an issue where the width of the element (and all child elements) would not decrease when resizing the page, resulting in horizontal scrolling on smaller screens. This was fixed by setting the base width and max-width of the element, and changing it in the media query. 

```css
.main-desktop {
  width: 100%;
  max-width: 375px;
}

.main-desktop {
    max-width: 650px;
  }
```

### Useful resources

- [CSS Grid Layout Guide](https://css-tricks.com/snippets/css/complete-guide-grid/) - Easy visual guide for Grid.
- [CSS Flexbox Layout Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Easy visual guide for Flexbox.
- [MDN Web Docs - Media query fundamentals](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Media_queries) - Tthe MDN page for media queries really helps to break down the basics and gain a clearer understanding of how media queries work. 

## Author

- Website - [DrewM64](https://github.com/DrewM64)
- Frontend Mentor - [@DrewM64](https://www.frontendmentor.io/profile/DrewM64)
