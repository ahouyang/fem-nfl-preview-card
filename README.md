# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements



### Links

- Solution URL: [https://github.com/ahouyang/fem-nfl-preview-card](https://github.com/ahouyang/fem-nfl-preview-card)
- Live Site URL: [https://ahouyang.github.io/fem-nfl-preview-card/](https://ahouyang.github.io/fem-nfl-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

As a newcomer to front end web development, I used this challenge as a way to reinforce content and concepts I had been learning in an online class.
I am very much still learning the fundamentals of everything, and in particular I found it challenging to use and understand flexbox in a practical
setting. I did gain a much better understanding of very basic positioning and formatting using flexbox, but I still have a lot to learn there. I used 
the following HTML/CSS to format the icons and labels for ETH and time left

```html
    <div class="label">
      <div class="icon-text">
        <img id="ether" class="it-icon" src="./images/icon-ethereum.svg" alt="">
        <strong class="primary" class="it-text">0.041 ETH</strong>
      </div>
      <div class="icon-text">
        <img id="clock" class="it-icon" src="./images/icon-clock.svg" alt="">
        <p class="secondary" class="it-text"> 3 days left</p>
      </div>
    </div>
```
```css
    .icon-text {
      display: flex;
      align-items: center;
      justify-content: space-evenly;
    }

    .it-icon {
      height: 30px;
    }

    .it-text {
      width: 100%;
    }
```

### Continued development

I will continue attempting basic challenges on frontendmentor to improve my understanding of fundamental front-end concepts. I still don't have the best understanding of flexbox, particularly all the sub-properties like flex, align-items, or justify-context, and I am continuing to learn best practices when it comes to tag organization/IDs/classes.

## Author

- Frontend Mentor - [@ahouyang](https://www.frontendmentor.io/profile/ahouyang)
