# Frontend Mentor - Fylo data storage component solution


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

- This is a solution to the [Fylo data storage component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![mobile-design](https://user-images.githubusercontent.com/49578782/159097159-f34be0c9-d426-4cf8-8e07-26e8ffa2e6f1.jpg)

![desktop-design](https://user-images.githubusercontent.com/49578782/159097201-65a1f672-f347-425e-be54-3f26308edeec.jpg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: https://fylo-data-storage.pages.dev/

## My process


- Go over the design images and visualize how i want to build it
- Set up the HTML using proper semantics and meaningful naming for the classes
- Start with mobile layout first then desktop layout going from top to bottom
- use devtools in browser to test responsiveness
- load the website in different browsers to make sure no odd behaviors occur

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Sass

### What I learned

- How to create a range slider from scratch without using input 


```html
 <div class="slider">
    <div class="gradient__slider"><span class="circle__slider"></span></div>
  </div>
```
```css
  .slider {
    height: 1.25rem;
    width: 100%;
    border-radius: 0.6rem;
    background-color: hsl(229, 57%, 18%);
    margin-top: 1rem;
    position: relative;

    .gradient__slider {
      height: 0.95rem;
      width: 75%;
      position: absolute;
      top: 50%;
      left: 0;
      transform: translatey(-50%);
      background-image: linear-gradient(to right, hsl(6, 100%, 80%), hsl(335, 100%, 65%));
      border-radius: 0.6rem;

      .circle__slider {
        width: 0.68rem;
        height: 0.68rem;
        background-color: config.$Pale_Blue;
        border-radius: 50%;
        display: block;
        position: absolute;
        top: 50%;
        right: 0.1rem;
        transform: translatey(-50%);
      }
    }
  }
```


### Continued development

- Improve my overall knowledge in sass since it's still new to me 
- Learn how to make different type of burger menu with animation 



## Author

- Frontend Mentor - [@Dblack84](https://www.frontendmentor.io/profile/Dblack84)
- Twitter - [@D_Black84](https://www.twitter.com/D_Black84)


