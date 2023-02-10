# CodeAcademy - "Colmar Academy" Final Project

This is a solution to the ['Colmar Academy' final project in CodeAcademy Course 'Build a Website with HTML, CSS, and Github Pages'](https://join.codecademy.com/learn/paths/learn-how-to-build-websites/).

## Table of contents

- [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
- [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

<p align="center">
  <img src="src/img/Снимок экрана 2023-02-10 в 19.31.58.png" alt="Project Photo"/>
</p>

### Links

-   Live Site URL: [https://yazdrahobycha.github.io/Colmar-Academy/](https://yazdrahobycha.github.io/Colmar-Academy/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Completing my first project was a significant achievement for me. Although the journey was filled with difficulties, I persevered and was able to create a comprehensive web page. The process was challenging, but I remained determined to overcome any obstacles that came my way.

The fullscreen banner was a particular highlight of the project for me. I was able to successfully create a visually appealing and impactful element of the page. I am proud of my accomplishment and feel that I have gained valuable experience and skills through this project:

<details>
<summary>HTMl</summary>
```html

<div class="banner flex">
    <div class="banner__container flex">
        <img
            class="banner__img"
            src="img/banner.jpg"
            alt="girl siiting on the desk"
        />
        <div class="banner__text flex">
            <h2>Learn something new everyday</h2>
            <h4>Lorem ipsum dolor sit amet consectetur adipisicing elit.</h4>
            <div class="button">
                <a href="#" class="button__link">Start Here!</a>
            </div>
        </div>
    </div>
</div>
```
</details>

<details>
<summary>CSS</summary>

```css
.banner {
    padding: 6rem 0 2rem 1.5rem;
    background-color: #495579;
    min-height: 100vh;
    align-items: stretch;
}

.banner__container {
    width: 100%;
    justify-content: flex-start;
}

.banner__container img {
    flex: 1 0 60%;
    height: 100%;
    border-radius: 20px;
    overflow: hidden;
    object-fit: cover;
}
```
</details>

### Continued development

- Develop a deeper understanding of adaptive image rendering.

- Familiarize oneself with the utilization of semantic HTML.

- Adopt a more concise coding style for enhanced readability by others.

- Optimize processes for improved efficiency.

- Elevate the use of animations and transitions for a more dynamic user experience.

## Author

- Instagram - [@yazdrahobycha](https://instagram.com/yazdrahobycha?igshid=YmMyMTA2M2Y=)
- Telegram - [Орсен](https://t.me/yazdrahobb)

## Acknowledgments

Big thanks to [Igor4ik](https://github.com/bigheha) for support!
