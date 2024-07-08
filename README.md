# CSS for JavaScript Developers - Huckleberry

This is a solution to the Josh W. Comeau's CSS for JavaScript Developers - Huckleberry workshop.

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
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![Huckleberry screenshot](./huckleberry-screenshot.png)

### Links

- Solution URL: [Huckleberry solution](https://github.com/jugglingdev/css-for-js-huckleberry)

## My process

### Built with

- HTML
- CSS float layout

### What I learned

In this challenge, I tackled solving the Huckleberry workshop with only float layout. That's right, no flexbox, grid, absolute positioning, `calc`, CSS variables, media queries or other advanced techniques. The purpose here was to get good at the basics: margin, padding, and border.

One big takeaway I have from this challenge is using `rem` units anytime you want the font or spacing to be able to scale as the user adjusts the font size on their computer. In this case, that included spacing between paragraphs. `px` can be used in other cases when the spacing doesn't need to adjust with the user preferences.

The other big takeaway from this challenge is thinking about reusable components. I initially had built the `max-width-wrapper` in the `header` and the one in `main` to have different margins to accommodate the `h2` styling. After watching Josh's solution video, I refactored those components to have the same styling so that they could be reusable. That required a little refactoring of the `main` elements, but with just a little effort, I think it simplifies the styles nicely.

### Continued development

In the future, I'd like to build my discernment of when float layout works and when advanced techniques like flexbox and grid are needed. I just to flexbox pretty quickly, so it would be nice to simplify when that's not needed. I'd also like to incorporate using `rem` and `px` units the way I learned in this module. Finally, I'm really curious to explore more ways to approach building reusable components and adjusting one-off styles.

### Useful resources

- [CSS for JavaScript Developers](https://css-for-js.dev/) - Helpful little guide for getting the random computer choice.

## Author

- Kayla Paden - Find me at [GitHub](https://github.com/jugglingdev), [freeCodeCamp](https://www.freecodecamp.org/jugglingdev), [Frontend Mentor](https://www.frontendmentor.io/profile/jugglingdev), [LinkedIn](https://www.linkedin.com/in/kayla-marie-paden)

## Acknowledgments

Thank you to [Josh W. Comeau](https://css-for-js.dev/) for a great course that makes you get your hands dirty even when going back to basics.
