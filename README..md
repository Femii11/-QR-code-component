# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview
The Challenge
Users should be able to:

View the optimal layout for the component depending on their device's screen size

See hover and focus states for interactive elements on the page
### Screenshot

![Project screenshot](./Screenshot%202026-09-04%20185958.png)



### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow
-Flexbox for layout centering and card structure

### What I learned

In this project, I focused on centering elements cleanly in the viewport and building a responsive card component using simple, clean CSS properties:

```CSS
div {
      display: flex;
      flex-direction: column;
      max-width: 300px;
      height: auto;
      width: 100%;
      text-align: center;
      background-color: hsl(0, 0%, 100%);
      border-radius: 10px;
      padding: 15px;
      margin: 0 auto;
      margin-top: 5%;
      margin-bottom: 5%;
      font-family: 'Outfit', sans-serif;
    }
```


To see how you can add code snippets, see below:

```html
 <main>
    <div>
      <span>
        <img src="./images/image-qr-code.png" alt="QR Code">
      </span>
      <span>
        <h1>Improve your front-end skills by building projects</h1>
        <p>Scan the QR code to visit the Frontend Mentor and take your coding skill to the next level</p>
      </span>
    </div>
  </main>
```

### Continued development

In future projects, I want to continue focusing on:

* **CSS Grid & Advanced Layouts:** Expanding beyond Flexbox to build more complex, multi-column web layouts.
* **Accessibility (a11y):** Ensuring proper ARIA attributes, focus states, and semantic landmarks for screen reader compatibility.
* **CSS Custom Properties & Design Tokens:** Organizing color palettes, typography scales, and spacing units dynamically using root CSS variables.
* **Mobile-First Responsive Design:** Fine-tuning media queries to ensure seamless scaling across various screen resolutions.

## Author
- Frontend Mentor - [@FEMII_DEV](https://www.frontendmentor.io/profile/FEMII_DEV)
- Twitter - [@femii_dev](https://www.twitter.com/femii_dev)

## Acknowledgments

* **[Frontend Mentor](https://www.frontendmentor.io)** - Thanks to Frontend Mentor for providing this fun component challenge to practice layout and responsive design.
* **[MDN Web Docs - Flexbox Guide](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)** - Great reference for understanding alignment and flex properties.
* **[codeliber](https://codeliber.com/)
** - Great for beginner who what to learn web development.

