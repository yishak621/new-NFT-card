# Frontend Mentor - NFT preview card component

![Design preview for the NFT preview card component coding challenge](./design/desktop-preview.jpg)

## Welcome! 👋# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

@yishak_abrham

## Overview

hey guys these is the best challenge to practice the overlay over an image using the relative and absolute positioning.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flex
- CSS Grid
- relative and absolute positioing

### What I learned

what really i learned in these project is testing my ablity to position elements absolute by positioning the parent element relatively.

<div class="card-img">
            <img src="./images/image-equilibrium.jpg" alt="" />
            <div class="card-overlay">
              <img
                src="./images/icon-view.svg"
                alt="Icon View"
                width="48"
                height="48"
              />
            </div>
          </div>
so when we hover over the card-img the hidden overlay image with background color will pop up by changing its opacity to 1.
```css
.card-overlay:hover {
  opacity: 1;
  transition: ease-out transform 0.8s;
}
To see how you can add code snippets, see below:
the overlay is enabled to be transparent 
background-image: url(./images/icon-view.svg) no-repeat center;
  background-color: hsl(
    178,
    100%,
    50%,
    0.5
  ); /*0.5 is opacity of color to enable transparency*/

and also the thin horizontal line is designed using horizontal row property
/_horizontal row line_/
hr {
border-bottom: 0;
border-left: 0;
border-right: 0;
border-top: 1px solid;
height: 10px;
color: var(--color-line);
margin-top: 1.5rem;
}

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

## Author

- Website - [Yishak abrham](https://github.com/yishak621)
- Frontend Mentor - [@yishak621](https://www.frontendmentor.io/profile/yishak621)

Thanks for checking out this front-end coding challenge.
