# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

(./screenshots/normal_state.png)
(./screenshots/active_state.png)
(./screenshots/mobile_screen.png)

### Links

- Solution URL: [Github repo](https://github.com/b16h22/social_links_profile_solution)
- Live Site URL: [Github pages](https://b16h22.github.io/social_links_profile_solution/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Centering a <div> element horizontally and vertically without providing hard values for padding or margin, with the help CSS flexbox.

```css
  .container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
  }
```
Adding active state for Title text element on hover.

```css
  .social:hover {
    color: hsl(0, 0%, 12%);
    background-color: hsl(75, 94%, 57%); 
    cursor: pointer;   
  }
```

### Useful resources

- [CSS Flexbox](https://www.w3schools.com/css/css3_flexbox_container.asp) - This is a good article that helped me understand CSS Flexbox and and it's potential.

## Author

- Frontend Mentor - [@b16h22](https://www.frontendmentor.io/profile/b16h22)