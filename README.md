# Profile card component solution

This is a solution to the ![Design preview for the Profile card component coding challenge](./design/desktop-preview.jpg). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

[Desktop version](./design/desktop-design.jpg)
[Mobile version](./design/mobile-design.jpg)

### Links

- [Solution URL](https://github.com/TMraz/Challenges/blob/main/Profile%20card%20component/index.html)

Repository URL: https://github.com/TMraz/Profile_card_component.github.io

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- MediaQuerries workflow
- [Styled Components](./css/style.css) - For styles

### What I learned

Snippets, see below:

```css
=== general setting ===

*,
*::after,
*::before {
  margin: 0;
  padding: 0;
  box-sizing: border-box;}
```
```css
=== centering the card ===

body:
    display: flex;
    justify-content: center;
    align-items: center;

```
```css
=== justify the background with multiple images ===

    background-color: #44B2C1;

    background-image: url(../img/bg-pattern-top.png), url(../img/bg-pattern-bottom.png);
    background-size: 80em, 80em;
    background-repeat: no-repeat, no-repeat;
    background-position: left -20em top -50em, right -20em bottom -50em;
```
```css
/* === MEDIA QUERRIES === */
@media screen and (max-width: 1440px) {
    body {
        background-size: 50em, 50em;
        background-repeat: no-repeat, no-repeat;
        background-position: left -20em top -30em, right -20em bottom -30em;    
    }
}
```

### Useful resources

- [Example resource 1](https://mdbootstrap.com/docs/standard/content-styles/background-image/#mdb872590335) - This helped me justify background images and position.
