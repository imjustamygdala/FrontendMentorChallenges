# Frontend Mentor - QRcode Component Solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

This was a faily simple challenge that took me only an hour or two to have the HTML completed and the CSS mostly working, but I did struggle with a few things.

### Screenshot

![](./wwwroot/screenshot.png)
<p>Screenshot from solution at 1440px</p>

### Links

- Solution URL: [Frontend Mentor Solution](https://www.frontendmentor.io/solutions/responsive-qrcode-card-using-css-grids-dtSzXOg1s6)
- Live Site URL: [Github Page](https://imjustamygdala.github.io/frontendmentor-qrcode-component/)

## My process

I started with a very basic HTML structure and I knew I only needed 2 divs. The first being the a main container, and the second being another container for the image and text.

I've also have been studying CSS Grids and saw an implementation where the grid was created on the body and pushed to the center of the screen using place-content: center. This seemed to be the simplest and most likely responsive approach at the moment.

I also used a bit of CSS boilerplate code to reset specific elements and to setup variables for the provided requirements.

That was my initial plan starting the project that I stuck with throughout project to the end.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid

### What I learned

The biggest learning moment for me, was most likely the time I spent creating the grid. I haven't spent much time with CSS Grids, or CSS styling, but I know how to do things like creating rows and columns. However, not so much on sizing them with the method I chose to implement. The supplied image is 576x576px which was way larger than I was expecting and caused the qr-component div to be way too big. I knew there would be resizing of elements, but I struggled getting the qr-component down to a proper size. Until I setup margins, paddings, and a max-width, I basically had a full screen height div element.

The first issue was getting the scale of content to not take up most of the entire screen. I setup a ```display: grid;``` and ```place-content: center;``` on the body so centering was easy, but the size of the column/row made the qr-component extremely large. I was able to resolve this issue by implementing a width on the main container, and I ultimately set a max-width for when the browser was at or above 1440pz.

The second, and most time consuming issue, was getting the image to center and scale properly. The image was adding a margin on its right side which threw off the padding of the qr-component. I was able to resolve this issue by setting ```margin: 0 auto```. The image will still create margins, but everything is evenly distributed in the div so the padding of the qr-component is now also evenly distributed.

### Continued development

This is the first challenge recommended by Frontend Mentor, so I plan to continue pursuing their challenges so I can better learn CSS.

### Useful resources

- Youtube: [Kevin Powell: Learn CSS Grid the easy way](https://www.youtube.com/watch?v=rg7Fvvl3taU) - This was an intro to CSS Grids I watched a while back, and referenced during this challenge.

## Author

- Frontend Mentor - [@imjustamygdala](https://www.frontendmentor.io/profile/imjustamygdala)