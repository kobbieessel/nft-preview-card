# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Solution screenshot](./images/images/screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL:(https://kobbieessel.github.io/nft-preview-card/)

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

I learnt
how to use classes and flex box.

```css
    <div class="date-container">
        <img src="/images/images/icon-clock.svg" alt="clock-icon" />
        <p>3 days left</p>
    </div>
```

```css
.date-container {
  padding: 0 5px;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
}
```

how to create overlay effect,how to use the position attribute and the difference between relative and absolute and how to use them.

```css
.image1 {
  position: relative;
  width: inherit;
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 5px;
  overflow: hidden;
}
```

```css
.overlay {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  width: inherit;
  background-color: hsla(178, 100%, 50%, 0.5);
  opacity: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  transition: 1s ease-in-out;
}
```

### Continued development

## Author

- Frontend Mentor - [@kobbieessel](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments
