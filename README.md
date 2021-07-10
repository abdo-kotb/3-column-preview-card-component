# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Improvements to the challenge](#improvements-to-the-challenge)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

Mobile Design
![screencapture-file-G-Programming-frontend-mentor-3-column-preview-card-component-main-index-html-2021-07-10-18_53_39](https://user-images.githubusercontent.com/86558336/125167157-33885b00-e1b0-11eb-844d-8ba729f74231.png)

Desktop Design
![screencapture-file-G-Programming-frontend-mentor-3-column-preview-card-component-main-index-html-2021-07-10-18_56_59](https://user-images.githubusercontent.com/86558336/125167255-af82a300-e1b0-11eb-8420-e72f9e9aeb70.png)

Button Active State
![screencapture-file-G-Programming-frontend-mentor-3-column-preview-card-component-main-index-html-2021-07-10-19_10_51](https://user-images.githubusercontent.com/86558336/125167639-a266b380-e1b2-11eb-9968-0beb06115043.png)

Attribution Active State
![screencapture-file-G-Programming-frontend-mentor-3-column-preview-card-component-main-index-html-2021-07-10-19_12_15](https://user-images.githubusercontent.com/86558336/125167689-dc37ba00-e1b2-11eb-87e4-cdf728d283c8.png)

### Links

- Solution URL: [Code on Github](https://github.com/abdo-kotb/3-column-preview-card-component)
- Live Site URL: [Live site URL](https://abdo-kotb.github.io/3-column-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Transform & Transition
- Animation
- Google Fonts
- [CSS Normalize](https://necolas.github.io/normalize.css/)
- Font Awesome Library

### Improvements to the challenge

I decided to not use the icons provided with the design assets in order to have the freedom to create some beautiful animation movements, and I would be happy if you notice them.
```css
i {
    animation: move 3s ease-in infinite forwards paused;
}
@keyframes move {
  0% {
    left: 0;
  }
  50% {
    left: 100%;
    transform: rotateY(0deg);
  }
  51% {
    transform: rotateY(180deg);
  }
  99% {
    transform: rotateY(180deg);
  }
  100% {
    left: 0;
    transform: rotateY(360deg);
  }
}
section:hover i {
  animation-play-state: running;
  color: var(--backgroundColor);
}
section:hover i::after {
  display: none;
}
```

## Author

- Git hub - [abdo-kotb](github.com/abdo-kotb)
- [Linkedin](https://www.linkedin.com/in/abdulrhman-mohammed-5687781b5/)
- Frontend Mentor - [@abdo-kotb](https://www.frontendmentor.io/profile/abdo-kotb)

Abdulrhman Kotb
