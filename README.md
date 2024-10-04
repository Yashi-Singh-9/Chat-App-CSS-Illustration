# Frontend Mentor - Chat app CSS illustration solution

[![Netlify Status](https://api.netlify.com/api/v1/badges/72b56c3b-3d22-400d-afd8-d767a0ea99b4/deploy-status)](https://app.netlify.com/sites/chat-app-css-iluustration/deploys)
[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) 
[![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS) 
[![Last Commit](https://img.shields.io/gitlab/last-commit/Yashi-Singh-9/chat-app-css-illustration?style=for-the-badge)](https://gitlab.com/Yashi-Singh-9/chat-app-css-illustration/-/commits/main)

This is a solution to the [Chat app CSS illustration challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/chat-app-css-illustration-O5auMkFqY). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- [Style Guide](#style-guide)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size.
- **Bonus**: See the chat interface animate on the initial load.

### Screenshot

#### Desktop Design

![Screenshot of my solution](design/desktop-design.jpg)

#### Mobile Design

![Screenshot of my solution](design/mobile-design.jpg)

### Links

- Solution URL: [Solution](https://www.frontendmentor.io/solutions/chat-app-css-illustration-EJxJ8EtOzE)
- Live Site URL: [Live](https://chat-app-css-iluustration.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox for layout
- Mobile-first workflow
- CSS animations for initial chat load

### What I learned

During this project, I reinforced my understanding of using **CSS animations** and **keyframes** to create smooth transitions for chat messages. The chat boxes slide in from opposite sides, simulating a real-time chat experience. 

Here’s an example of a CSS animation I applied:

```css
@keyframes slideIn {
    100% {
        transform: translateX(0);
    }
}

.chat-left-container, .chat-right-container {
    animation: slideIn 1s ease-in forwards, fadeIn 1s ease-in forwards;
}
```

Additionally, I improved my mobile-first design approach, ensuring that the app’s layout looks clean and functional on both desktop and mobile devices.

### Continued development

I plan to explore more about:

- **Accessibility**: Adding ARIA attributes and making the app more usable for screen readers.
- **Advanced CSS animations**: Using more complex animations and transitions to enhance user experience.
- **Responsiveness**: While the layout is mobile-first, I aim to improve responsiveness across different screen sizes.

### Useful resources

- [MDN Web Docs - CSS Animations](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations) - This helped me understand how to use `@keyframes` and apply animation properties effectively.
- [CSS Tricks - A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This article was incredibly useful for laying out my components using Flexbox.

## Style Guide

For Style Guidance please refer to [Style Guide File](style-guide.md)

## Author

- Frontend Mentor - [@Yashi-Singh-9](https://www.frontendmentor.io/profile/Yashi-Singh-9)
- LinkedIn - [Yashi Singh](https://www.linkedin.com/in/yashi-singh-b4143a246)

## Acknowledgments

Thanks to the Frontend Mentor community for providing great challenges and resources. Special thanks to anyone who provided feedback and guidance on improving this solution.