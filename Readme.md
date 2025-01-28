# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- See hover and focus states for all interactive elements on the page



### Links

- Solution URL: [https://github.com/DiPSAWCE/SOCIAL-LINKS-PAGE]
- Live Site URL: [https://dipsawce.github.io/SOCIAL-LINKS-PAGE/]

## My process

### 1.intial setup
- I created the basic html structure
- Implemented the css reset for -Consistent cross browser rendering
- Set up the inter font family by going to Google fonts and connecting to the font via embedd code
- converted the given base colors from hsl to Hex which is easier to work with.

### 2.Core container structure
- Created section with main container i.d
- implemented card_style design with rounded corners.
- set up initial spacing and padding system.
- Created social links list structure.

### 3.Profile components
- Added avatar image container, I went for a square design as i decide to tweak the project for my own personal links
- Implemented links for the list section.

### 4. Styling elements
- - Applied consistent color scheme:
  - Background: Black (#000000)
  - Container: Dark Gray (#141414)
  - Accent: Lime Green (#C5F82A)
  - Text: White (#FFFFFF)
- Added hover effects on interactive elements
- Implemented smooth transitions for better user experience


### 5. Responsive Design Implementation
- Mobile first approach using media queries
  - Mobile devices (max-width: 480px)
  - Tablets (481px - 768px)
  - Desktop (769px and above)
  - Large screens (1200px+)

### 6. Key Features
- Fully responsive design
- Dark theme with high contrast
- Interactive hover states
- Smooth transitions
- Mobile-optimized interface
- Flexible container sizing
- Cross-browser compatibility


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned
I learnt the importance of responsive design in morden web development. I Learnt the importance of child and parent elements.

I also learnt the best methods for cross-device compatibility using media queeries.




```html
   <ul class="links-menu">
                    <li><a href="https://github.com/DiPSAWCE">Github</a></li>
                    <li><a href="https://www.frontendmentor.io/profile/DiPSAWCE">Frontendmentor.io</a></li>
                    <li><a href="https://x.com/mjayeziinnooo?s=21">Twitter</a></li>
                    <li><a href="https://www.instagram.com/mjayezi.innooo_?igsh=MTA3d3c0Ym9pZ21jbw%3D%3D&utm_source=qr">Instagram</a></li>
               
```
```css
.proud-of-this-css {
 .links-menu li a {
    background-color: #333333;
    text-decoration: none;
    color: white;
    width: 304px;
    height: 45px;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 4px;
    font-weight: 700;
    transition: all 0.2s ease-in-out;
}






### Continued development
- 1.I would like to learn how to add a dark or light theme toggle.
- 2. Adding a social media preview metadata



### Useful resources

- [https://www.youtube.com/watch?v=MUPKRoEOChU] - This helped me  alot as the guy takes you through the whole process of designing the social links page.



## Author

- Website - [Banele Mjayezi](https://github.com/DiPSAWCE/SOCIAL-LINKS-PAGE/blob/main/index.html)
- Frontend Mentor - [@DiPSAWCE](https://www.frontendmentor.io/profile/DiPSAWCE)
- Twitter - [@mjayeziinnooo](https://x.com/mjayeziinnooo)

*

## Acknowledgments

A major thank you to my frontend sensei Jeanette de Ward.
