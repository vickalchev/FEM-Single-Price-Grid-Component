# Frontend Mentor - Single price grid component

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

The main goal of this challenge is to practice setting up a layout of a component using different approaches: flexbox, CSS Grid, Bootstrap, etc. My solution uses CSS grid, as we are dealing with a brid of boxes stacked together.

This is my first challenge, so it took me approximately 14 hours to complete. I used various reference materials (overstack flow, MDN,etc.) and the solutions of other developers to guide me through some of the more challenging components.

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](/images/Screenshot-Solution.jpeg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

- I started by examining the grid and its components. In this case, we had three boxes stacked on top of each other. This told me that CSS Grid or Flexbox would be the methods of choice.
- The three areas of the price component were wrapped in another area with rounded corners. This is why, I had to set up a wrapper.
- I started by setting up a <main> section, which I was going to use as a wrapper. In other solutions I noticed developers had created classes, however, I thought this was unnecessary. I used the <main> tag in CSS to modify the look of the main component.
- I nested each of the three main sections as <div>'s within <main> and applied two classes on them: "padding" and "section1", "section2", "section3" respectively. The "padding" class applied to all <div>'s as I was going to use it to apply universal padding on all sections.
- I used classes "section1", "section2" and "section3" to assign grid areas in the stylesheet using template-grid-areas.
- Getting the layout to match the design was the hardest part of the exercise and what took me the longest. Tinkering with alignment and colour was easier even though also time-consuming.
- To make the solution responsive to various screen sizes, I used @media tag.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

- template-grid-areas are amazing. It was hard to get the hang of them but once I did some research and got the logic they made sense. I love how you can assign a component in the stylesheet to a grid and customize it.
- It's helpful to think of a design request in terms of a grid, especially when it comes to setting up a layout.
- What seems simple is actually more difficult.

```css
display: grid;
grid-template-areas:
  "section1 section1"
  "section2 section3";
```

### Continued development

- CSS Grid
- media tags

## Author

- Website - [PivotUP](https://pivotup.co)
- Frontend Mentor - [@vickalchev](https://www.frontendmentor.io/profile/vickalchev)
- Twitter - [@vickalchev](https://www.twitter.com/yourusername)
