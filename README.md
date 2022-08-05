# NFT-preview-card
A responsive preview card
# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

### Links

- Solution URL: https://github.com/nwakego98/NFT-preview-card.git
- Live Site URL: 

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- [Styled Components](https://styled-components.com/) - For styles

### What I learned
i learn how to transition from one image to another using hover

```html
<div class="card">
            <img src= "image-equilibrium.jpg"alt="Card Back">
            <img src="icon-view.svg "  class="img-top" alt="Card Front">
        </div>
```
```css
.card img{
    position: relative;
    display: inline-block;
    justify-content: center;
    align-items: center;
    min-height: 250px;
    width: 100%;
    border-radius: 10px;
}

.card .img-top {
    display: none;
    position: absolute;
    top: 0;
    left: 0;
    z-index: 99;
}
.card:hover .img-top {
        display: inline;
     background-color: hsl(178, 100%, 50%) ;
     opacity: 0.50;
    }


### Continued development
basically CSS(opacity ,hover, transitioning from one image to another during hover)

### Useful resources
- [Example resource 1](https://www.w3schools,com) - This helped me to set the back and front image after the hover and also to set the opacity. I really liked this pattern and will use it going forward.

## Author
- Website -(https://app.netlify.com/teams/nwakego98)
- Frontend Mentor - (https://www.frontendmentor.io/profile/nwakego98)
- Twitter - (https://www.twitter.com/GlowRee17?t=wvddWNyWznpHL13CvpRMyg&s=08)





