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

## Table of contents

- [Overview](#overview)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

I used the style guide from the figma design of the Testimonial Grid pattern, then make it responsive for Desktop & Mobile.

| Mobile View                                     | Desktop View                                      |
| ----------------------------------------------- | ------------------------------------------------- |
| ![Mobile](./images/Testimonial-Grid-Mobile.png) | ![Desktop](./images/Testimonial-Grid-Desktop.png) |

<!-- | Mobile View                                     | Desktop View                                      |
| ----------------------------------------------- | ------------------------------------------------- |
| <img src="./images/Testimonial-Grid-Mobile.png"/> | <img src="./images/Testimonial-Grid-Desktop.png"/>  | -->

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

How to utilise CSS Grid to make the layout.

To see how you can add code snippets, see below:

```css
<h1>Some HTML code I'm proud of</h1>
```

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

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
