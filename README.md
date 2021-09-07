# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./Frontend Mentor Testimonials-grid-section screenshot-laptop.png)
![](./Frontend Mentor Testimonials-grid-section screenshot-mobile.png)


### Links

- Solution URL: [Solution URL here](https://github.com/Memeena/testimonial-grid-section)
- Live Site URL: [Live site URL here](https://memeena.github.io/testimonial-grid-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow

### What I learned

I learnt how to use Grid in this scenario. First I determined the size of the grid by considering the smallest area and kept it as 1 cell. Then I calculated the cells for rows and columns. Here in this challenge, 
  
  - the first cell spans across 2 columns in the first row
  - the second cell is just one column and 1 row
  - third starts in the second row and spans 1 column
  - fourth starts in second row and spans 2 column
  - fifth starts in first row and spans 2 rows.

While the viewport size decreases, it automatically fits the screen size since I have used auto-fit and minmax property.

This makes it easy when for mobile use, since not much coding is needed. But I had a problem when tried to display all the cells in a single column. Since I have explicitly given where the cell should be placed in the row and column using grid-row and grid-column, it did not change as it should be. So I had to change this part for screen size less than 900px where it changes to single column.

## Author

- Website - [Meenakshi]
- Frontend Mentor - [@meMeena](https://www.frontendmentor.io/profile/Memeena)

