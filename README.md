# Order summary card solution


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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview
Below is a general description about the development of this project.

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![Screenshot](screenshot.png)



### Links

- Solution URL: [](https://github.com/JorgeR-Code/Order-summary-card.git)
- Live Site URL: [](https://suscripcion.jorgerivera.me)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles



### What I learned

The most important learning I achieved with this project was the use of "Flexbox" to be able to distribute elements correctly and efficiently. Since this allows the distribution of the elements that are required in a very versatile way.

As for example, below is a CSS code where it was very important to make use of "Flexbox", since it was necessary for both the parent div (.container) as well as for the child div (.card).

```css

.container {
    width: 100%;
    height: 100vh;
    padding: 10vmax 0;
    align-items: center;
    display: flex;
    justify-content: center;

}

.card {
    background-color: white;
    width: 400px;
    height: 90%;
    min-height: 654px;
    max-height: 654px;

    display: flex;
    flex-direction: column;
    justify-content: space-between;
    border-radius: 15px;
    text-align: center;
    position: absolute;
    margin: auto;
}
```





### Continued development

The areas of my interest are the dynamic and interactive part of a web application, that is, that which allows interaction between several pages in order to manage information and data.

### Useful resources

- [resource 1](https://developer.mozilla.org/es/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox) - This helped me manage element positioning with Flexbox.


## Author

- Website - [Jorge Rivera](https://www.jorgerivera.me)
- Github - [JorgeR-Code](https://github.com/JorgeR-Code)



