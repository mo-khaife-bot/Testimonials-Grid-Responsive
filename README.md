<h1 align="center">{ 💬 Testimonials Grid 💻 Desktop & Mobile 📱 }</h1>

<div align="center">
  <h3>
    <a href="https://responsive-404-page.netlify.app/">
      Demo
    </a>
    <span> | </span>
    <a href="https://github.com/mo-khaife-bot/responsive-404-not-found">
      Solution
    </a>
    <span> | </span>
    <a href="https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7">
      Challenge
    </a>
  </h3>
</div>

<br>

## Table of contents

- [Overview](#overview)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Author](#author)

<br>

## Overview

The goal is to build out this testimonials grid section and get it looking as close to the Figma design as possible, and make it responsive with an emphasis on mobile first.

| Mobile View                                     | Desktop View                                      |
| ----------------------------------------------- | ------------------------------------------------- |
| ![Mobile](./images/Testimonial-Grid-Mobile.png) | ![Desktop](./images/Testimonial-Grid-Desktop.png) |

## Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow via Media Queries

<br>

## What I learned

How to utilise CSS Grid to make the layout.

```css
.card--bg-gray-blue {
  background-color: var(--primary-grayish);
  color: #fff;
}

.card--bg-black-blue {
  background-color: var(--primary-blackish);
  color: #fff;
  grid-area: patrick;
}
.card:nth-of-type(5) {
  grid-area: kira;
}
}
```

```css
.wrapper {
  display: grid;
  gap: 30px;

  grid-template-areas:
    "daniel daniel jonathan kira"
    "jeanette patrick patrick kira";
  grid-template-columns: repeat(4, 1fr);
}
```

<br>

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)
