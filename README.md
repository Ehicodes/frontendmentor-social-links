# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

In this project, I was tasked to build a social link-sharing profile which could be personalized to be used to share my social profiles.

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![My Social Profile Card Solution](./assets/images/Screenshot%202026-09-11%20at%208.14.10%20AM.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [(frontendentor-social-links.netlify.app)]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- BEM Methodology
- Desktop-first workflow

### What I learned

I am really proud of how I resolved the layout challenges in this project. Specifically, I learned how to prevent the profile image from stretching when clipping it into a perfect circle using `object-fit: cover`. Additionally, I successfully managed the page layout by using absolute positioning to keep the attribution pinned neatly to the bottom without disrupting the vertical centering of the main card component.

```css
.social-card__image{
    width: 7rem;
    height: 7rem;
    border-radius: 50%;
    object-fit: cover;
}

.attribution{
    position: absolute;
    bottom: 1rem;
    color: hsl(0, 0%, 100%);
    font-size: 1.2rem;
    width: 100%;
    text-align: center;
    a{
        color: hsl(75, 94%, 57%);
        text-decoration: none;
    }
}
```

## Author

- Github - [Ehinomen Osaigbovo](https://github.com/Ehicodes)
- Frontend Mentor - [@Ehicodes](https://www.frontendmentor.io/profile/Ehicodes)
- X - [@Ehinomen_01](https://x.com/ehinomen_01?s=11)

