## Table of contents

- [Overview](#overview)
  - [User story](#user-story)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Highlights](#hightlights)
- [Author](#author)

## Overview

### User story

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./assets/images/Screenshot%202025-07-06%20160641.png)

### Links

- Solution URL: [Github Repository](https://github.com/SteveNoyes/blog-preview-card)
- Live Site URL: [Github Pages](https://stevenoyes.github.io/blog-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### Hightlights

```html
  <div class="blog-preview-wrapper">
    <img src="./assets/images/illustration-article.svg" alt="Abstract Code on a Yellow Background">
    <div class="category">Learning</div>
    <p class="pub-date">Published 21 Dec 2023</p>
    <h2>HTML & CSS foundations</h2>
    <p class="description">These languages are the backbone of every website, defining structure, content, and presentation.</p>
    <div class="author-info">
      <img src="./assets/images/image-avatar.webp" alt="Author Profile Picture">
      <p>Greg Hooper</p>
    </div>
  </div>
```

```css
  @font-face {
    font-family: 'Figtree Extra Bold';
    src: url('../fonts/Figtree-ExtraBold.woff2') format('woff2'),
        url('../fonts/Figtree-ExtraBold.woff') format('woff'),
        url('../fonts/Figtree-ExtraBold.ttf') format('truetype');
    font-weight: bold;
    font-style: normal;
    font-display: swap;
  }

  @font-face {
    font-family: 'Figtree Medium';
    src: url('../fonts/Figtree-Medium.woff2') format('woff2'),
        url('../fonts/Figtree-Medium.woff') format('woff'),
        url('../fonts/Figtree-Medium.ttf') format('truetype');
    font-weight: 500;
    font-style: normal;
    font-display: swap;
  }
```

## Author

- Website - [Steven Noyes](https://www.stevenmnoyes.com)