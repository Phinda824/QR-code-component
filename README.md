# QR-code-component
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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./image/Solution.png)

### Links

- Solution URL: (file:///C:/Users/siman/Documents/QR%20Code%20Component/index.html)
- Live Site URL: (http://127.0.0.1:5500/index.html)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid

### What I learned
- add a background-color
- change a font-size
- to align and the margins

```html
    <head>
        <link rel="icon" type="image/png" sizes="32x32" href="./image/favicon-32x32.png"/>
    </head>
    <body>
        <main class="cont">
            <section class="code">
                <header class="text">
                    <div class="picture">
                        <img src="./image/image-qr-code.png" alt="Ladies in an office space">
                    </div>
                </header>
            </section>
        </main>

    </body>
```
```css
body {
    display: flex;
    min-height: 100vh;
    justify-content: center;
    text-align: center;
}

.cont {
    justify-content: center;
    text-align: center;
    margin: auto;
}
.code {
    padding: 15px;
    border-radius: 19px;
    background-color: hsl(0, 0%, 100%);
}

.text h1 {
    padding: 16px;
}

.text p {
    margin-bottom: 20px;
}

.picture img {
    max-width: 100%;
    border-radius: 19px;
}
```
### Continued development

## Author

- Website - [Phinda]
- Frontend Mentor - [@Phinda824]

## Acknowledgments

I appriciate for giving me a chance for doing this challenge. I have gained some Basics for this project.
