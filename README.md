# blog-preview-card
# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

> 💡 These are just the design sizes. Ensure content is responsive and meets WCAG requirements by testing the full range of screen sizes from 320px to large screens.

## Colors

### Primary

- Yellow: hsl(47, 88%, 63%)

### Neutral

- White: hsl(0, 0%, 100%)
- Grey: hsl(0, 0%, 50%)
- Black: hsl(0, 0%, 7%)

## Typography

### Body Copy

- Font size (paragraph): 16px

### Font

- Family: [Figtree](https://fonts.google.com/specimen/Figtree)
- Weights: 500, 800

> 💎 This is a free+ challenge. So, if you want to see all the design details and practice working with professional tools like Figma, you can download the design file from where you downloaded the starter code.

/* Frame 3 */

box-sizing: border-box;

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 24px;
gap: 24px;

position: absolute;
width: 327px;
height: 501px;
left: calc(50% - 327px/2);
top: calc(50% - 501px/2 - 0.5px);

background: #FFFFFF;
border: 1px solid #111111;
box-shadow: 8px 8px 0px #000000;
border-radius: 20px;
