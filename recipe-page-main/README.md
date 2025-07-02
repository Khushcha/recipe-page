# Frontend Mentor - Recipe page solution


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

The challenge was to build out a recipe page for a simple omelette, replicating the provided design as closely as possible. The solution includes a responsive layout with interactive elements like collapsible sections, timers for cooking steps, and a toggle for nutritional information, enhanced with modern CSS styling.

### Screenshot

![Screenshot](assets\images\Screenshot.png)


### Links

- Solution URL:https://github.com/Khushcha/recipe-page
- Live Site URL:  https://khushcha.github.io/recipe-page

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- JavaScript for interactivity


### What I learned
During this project, I learned how to implement interactive elements like collapsible sections and timers using JavaScript, and how to enhance a design with advanced CSS techniques such as animations, gradients, and hover effects. A key takeaway was optimizing responsiveness across different screen sizes, which improved my understanding of media queries and layout adjustments.


```html
<div class="section ingredients">
  <h3 onclick="toggleCollapse('ingredients-list')">Ingredients</h3>
  <ul id="ingredients-list" class="collapsible">
    <li>2-3 large eggs</li>
  </ul>
</div>
```
```css
.section:hover {
  transform: translateY(-4px);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.05);
}
```
```js
function toggleCollapse(id) {
  const element = document.getElementById(id);
  element.classList.toggle('hidden');
}
```



### Continued development

I plan to focus on mastering CSS Grid for more complex layouts and exploring advanced JavaScript animations to create even more engaging user experiences. I also want to deepen my knowledge of accessibility to ensure my projects are inclusive.

### Useful resources

- CSS Tricks - Animations - Helped me understand and implement smooth transitions.
- MDN Web Docs - JavaScript Timers - A great resource for learning about timer implementation.



## Author

- Website - Khushbu Chaurasia (http://127.0.0.1:5500/recipe-page-main/index.html)
- Frontend Mentor - @Khushcha (https://www.frontendmentor.io/profile/Khushcha)


## Acknowledgments

I completed this challenge almost on my own , solved small problems with the help of ChatGPT.
