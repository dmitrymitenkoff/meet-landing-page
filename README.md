# Meet landing page project

## Table of contents

- [Overview](#overview)
  - [The project](#the-project)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The project

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Centering in CSS can be achieved in a number of ways. In this project I focussed on using CSS flexbox properties for centering elements on the page. For horizontal centering, I used the tried method of setting an element's margin to "auto":
```css
.container {
  margin: 0 auto;
}
```
To center in both directions (ie horizontally and vertically), I used the following flexbox properties on the parent element, like so: 
```css
.feature {
  display: flex;
  justify-content: center;
  align-items: center;
}
``` 

I also used a background shortcut property for setting up the hero background images in CSS; I worked out the following order of background properties: image url, position, size, repeat:
```css
.right-hero {
  background: 
    url('./assets/desktop/image-hero-right.png')
    left / contain
    no-repeat;
}
``` 
Finally, I used the thematic break horizontal rule element in HTML for creating the transition from one section to another. I opted to use this element as I felt it was semantically justified as it signifies a change of scene in a story or section.

### Continued development

In future projects, I'm planning to focus on developing the layouts using the grid system. I also need to improve my understanding of using a set width for layouts and when it's best to use CSS grid or flexbox as opposed to hardcoding the width using px or other relative units and setting the margin to auto. 


### Useful resources

- [The Thematic Break Horizontal Rule element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/hr) - This helped me for making my html more semantic. Applying styles to the element is straightforward. 
- [Media Queries for Standard Devices - an overview](https://css-tricks.com/snippets/css/media-queries-for-standard-devices/) - This is a handy overview and provides and updated information for a variety of devices and best practising for setting up media queries.  
- [Centering in CSS: A Complete Guide](https://css-tricks.com/centering-css-complete-guide/) - This is an amazing article which helped me center the entire content of the page. I'd recommend it to anyone still learning this concept as it features a number of ways for centering elements on a page, especially using the mordern technology such as flexbox and grid. 
- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This is a flexbox bible and I think every developer already uses this source, as I think it's the best explanation of how various flex properties behave.  
- [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - As above - saves you a ton of time coding your layouts.
- [A Complete Guide to Links and Buttons](https://css-tricks.com/a-complete-guide-to-links-and-buttons/) - This is the best explanation on when to use links, buttons and HTML inputs in HTML, CSS and JS. The article discusses markup implementation, related attributes, best practices for styling and things to avoid. 
- [Background property on MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/background) - A wealth of information on the background shorthand property in CSS.  

## Author

- Twitter - [@walzinthedesert](https://www.twitter.com/walzinthedesert)
