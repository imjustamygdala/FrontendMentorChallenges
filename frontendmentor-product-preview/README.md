# Frontend Mentor - Product Preview Card Component Solution

This is a solution to the [Product Preview Card Component Challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

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
This challenge was fairly easy to structure within the HTML, but creating a layout for the container that contained the product information proved to be difficult for me. This was a fun challenge, but I ultimately had to use a Kevin Powell video that went over this challenge for help. However, I was able to create a very similar HTML markup and layout within CSS for the image container and product info container, but I needed help with tying everything together, which is where the video came in handy.

The one thing that Kevin mentioned is to not get too caught up on the widths of each element in the product content container. He emphasized not worrying too much about making sure the widths are an exact match to the provided design files since there is too much you have to eyeball using Frontend Mentors free package and you could waste a lot of time trying to get those things perfect while there are bigger fish to fry. This stuck out a lot to me and was a problem I had with my first iteration of this project.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./wwwroot/screenshot.png)
<p>Screenshot from solution at 375px</p>

### Links

- Solution URL: [Frontend Mentor Solution](https://your-solution-url.com)
- Live Site URL: [Github Page](https://imjustamygdala.github.io/frontendmentor-product-preview/)

## My process
I started with a basic HTML structure and I knew that I would need a container for the product, a container for the image, a container for the product content, and a container for the prices.

I really enjoy using CSS Grids, so I created a grid on the body, and then originally tried to create a grid for the image container and product content container. However, I ended up using flex for the prices and the `<picture>` element to wrap the `<image>` tag so I could utilize `srcset="" media="(min-width:)` for swapping images at a lower resolution.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned about using the `<picture>` tag to dynamically swap images as well as implementing flex within a grid layout. I also continue to learn about better semantics with CSS such as custom properties within selector and then doing something like a media query to adjust the custom property that will dynamically update all use cases of the custom property while the media query is active.

### Continued development

I still have a lot to learn when it comes to CSS and HTML semantics, so I plan to continue learning about both subjects to hopefully be able to more implement best practices effortlessly in the future.

### Useful resources

- [Kevin Powells YouTube - Frontend Mentor Challenge](https://www.youtube.com/watch?v=B2WL6KkqhLQ) - After I got stuck and needed direction, this obviously pushed me in the right direction. I do recommend at least trying this solution for yourself before watching his video.

## Author

- Frontend Mentor - [@imjustamygdala](https://www.frontendmentor.io/profile/imjustamygdala)