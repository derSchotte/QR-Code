# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Frontend Mentor - QR code component solution](#frontend-mentor---qr-code-component-solution)
    -   [Table of contents](#table-of-contents)
    -   [Overview](#overview)
        -   [Screenshot](#screenshot)
        -   [Links](#links)
    -   [My process](#my-process)
        -   [Built with](#built-with)
        -   [What I learned](#what-i-learned)
        -   [Continued development](#continued-development)
        -   [Useful resources](#useful-resources)
    -   [Author](#author)

## Overview

### Screenshot

![Solution screenshot](solution/screenshot.png)

### Links

-   Solution URL: [QR-Code GitHub Repo](https://github.com/derSchotte/QR-Code)
-   Live Site URL: [QR-Code Netlify](https://bucolic-melomakarona-ad1dc1.netlify.app/)

## My process

### Built with

-   HTML markup
-   CSS custom properties
-   Flexbox

### What I learned

Now I know, how to implement Google-Fonts in my project. Because I used a Google-Font for the first time.
Normaly I directly implement my fonts from a folder inside my project.

```css
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap');

:root {
    --pureWhite: hsl(0, 0%, 100%);
    --lightGray: hsl(212, 45%, 89%);
    --grayishBlue: hsl(220, 15%, 55%);
    --darkBlue: hsl(218, 44%, 22%);
}

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

html,
body {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100vw;
    height: 100vh;
    background: var(--lightGray);
    font-family: 'Outfit';
}
```

### Continued development

I want to learn more about the Flexbox and Grid. I think, that I can use it more efficient.

### Useful resources

-   [Google Fonts](https://fonts.google.com/knowledge/using_type/using_web_fonts_from_a_font_delivery_service) - This helped me to understand how to implement Google-Fonts in my project.

## Author

-   Frontend Mentor - [@derSchotte](https://www.frontendmentor.io/profile/derSchotte)
