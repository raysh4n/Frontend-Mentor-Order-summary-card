# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot
<br>Desktop<br>
![](./desktop%20Screenshot%202025-01-21%20at%2020-25-07%20Frontend%20Mentor%20Order%20summary%20card.png)

<br>Mobile<br>
![](./mobile%20Screenshot%202025-01-21%20at%2020-25-26%20Frontend%20Mentor%20Order%20summary%20card.png)


### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/responsive-order-summary-card-P1L5YxG3zH)
- Live Site URL: [Add live site URL here](https://fem-order-summary-card-raysh3n.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

- just using normal hero image without any css properties for this project
```html
<img
                src="/images/illustration-hero.svg"
                class="card__image"
                alt="woman dancing while listening to music"
            />
```

to achieve the background look, has to put in background color as well
```css
@media (min-width:768px) {
    body {
        /* height: 100vh; */
        background-image: url('/images/pattern-background-desktop.svg');
        background-size: contain;
        background-repeat: repeat-x;
        /* background-position:0px -200px;  */
        background-color: var(--clr-pale-blue);
    }

}
```




