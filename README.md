
# Frontend Mentor - Recipe Page Solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

* [Overview](#overview)

  * [The challenge](#the-challenge)
  * [Screenshot](#screenshot)
  * [Links](#links)
* [My process](#my-process)

  * [Built with](#built-with)
  * [What I learned](#what-i-learned)
  * [Continued development](#continued-development)
  * [Useful resources](#useful-resources)
* [Author](#author)

---

## Overview

### The challenge

Users should be able to:

* View the optimal layout depending on their device’s screen size
* See hover and focus states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

* Solution URL: (https://github.com/tech-goddezz/Recipe-Page.git)
* Live Site URL: (https://recipe-page-lac-three.vercel.app/)

---

## My process

### Built with

* Semantic HTML5 markup
* CSS custom properties
* Flexbox
* Mobile-first workflow

### What I learned

While building this project I improved my skills in:

* Structuring a page with **semantic HTML elements** (`<main>`, `<article>`, `<header>`, `<section>`, `<figure>`) for accessibility.
* Using **CSS variables** for colors, spacing, and typography to create a simple design system.
* Applying **fluid typography** with `clamp()` to make headings scale across devices.
* Customizing list markers with `::marker` to match the design.

Here’s an example of fluid typography I implemented:

```css
.head_title {
  font-size: clamp(1.5rem, 1.2rem + 3vw, 2.5rem);
}
```

### Continued development

In future projects, I want to:

* Deepen my understanding of **accessibility** (ARIA roles, screen reader testing).
* Practice **CSS Grid** for more complex layouts.
* Explore **performance optimizations** such as lazy loading images and responsive image formats.

### Useful resources

* [MDN Web Docs](https://developer.mozilla.org/) — For HTML, CSS, and accessibility references.
* [CSS Tricks: clamp() guide](https://css-tricks.com/linearly-scale-font-size-with-css-clamp-based-on-the-viewport/) — Helped me understand and apply fluid typography.

---

## Author

* Frontend Mentor – [@yourusername](https://www.frontendmentor.io/profile/yourusername)
* Twitter – [@yourusername](https://www.twitter.com/yourusername)

