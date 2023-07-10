# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Author](#author)

## Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

## What I learned

1. Link Google font to HTML

    ```html
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap" rel="stylesheet">
    ```

1. Insert image to HTML page

    ```html
    <img src="images/qr-code.png" id="jojoberlari">
    ```

1. Put `div` elemen in the center of screen using Flexbox
  
    ```css
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100vw;
    height: 100vh;
    ```
  
1. Using CSS variable
  
    ```css
    --white: hsl(0, 0%, 100%);
    background-color: var(--white);
    ```

## Author

- Clarisa Helena
