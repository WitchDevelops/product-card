# About

It's my first completed frontend mentor challenge - this one can be found here: [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

Design: 
![Design for the desktop version](./design/desktop-design.jpg)
![Design for the mobile version](./design/mobile-design.jpg)

Goals:
1. Code a fully responsive page
2. Add active states to the button to indicate interaction.

# Solution to the challenge

Screenshots of the finished challenge:

# Link
Live solution can be viewed here: [https://witchdevelops.github.io/product-card/](https://witchdevelops.github.io/product-card/)

# Build with
* semantic HTML5 markup
* CSS custom properties
* Flexbox
* Mobile-first workflow
* Responsive web design principles

# What I learned
I learned about the <code>picture</code> tag! It allows to provide a set of alternative images and let the browser decide which image to serve, based on provided requirements (like viewport width and resolution). It's very useful, as it helps to optimize the experience for the end user.

Here is a code snippet that illustrates this:

```<picture>
     <source media="(min-width: 1440px)" srcset="./images/image-product-desktop.jpg">
     <img src="./images/image-product-mobile.jpg" alt="a big bottle of perfume by Channel">
    </picture>
```
It tells the browser to serve a bigger image on wider screens, with having a fallback image for older browsers and smaller screen sizes.
I will definitely use it more in the future.
