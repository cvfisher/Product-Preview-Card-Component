# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- Live Site URL: [Add live site URL here](https://cvfisher.github.io/Product-Preview-Card-Component/)

## My process

### Built with

- Vanilla CSS
- Flexbox

### What I learned

Building this project reinforced my knowledge of Flexbox and layout structure. A challenge I came across was text overflowing its container when I resized the window, until I realised it was because the image had a fixed width and wasn't responsive. This was rectified by using dynamic measurements, and I learned a lot about which measurement is often best for each use case. I also learned `display: none` to seamlessly change the product image once the screen reaches smaller resolutions.

```html
<h1>Some HTML code I'm proud of</h1>
```

```css
.hero-img-2 {
  display: none;
}

@media (min-width: 481px) and (max-width: 768px) {
  body {
    padding: 0 5vw 2vw 5vw;
  }
  .card {
    display: flex;
    flex-direction: column;
    width: 80%;
  }
  .hero-img {
    display: none;
  }
  .hero-img-2 {
    display: block;
    border-radius: 15px 15px 0 0;
  }
}
```

```js
const proudOfThisFunc = () => {
  console.log("🎉");
};
```

### Continued development

I would like to continue practicing with Flexbox and Grid to build responsive, more complex layouts. To do this I want to gain a deeper understanding of how parent and child elements interact with eachother and responsive units, as I felt like I was guessing unit sizes more than a few times.

### Useful resources

- [CSS Units Explained](https://www.youtube.com/watch?v=fzZTvLmmTzM) - This really helped me understand how each unit works and when to use them. A very good breakdown that I will likely refer back to.
- [Media Queries Max and Min Screen Width for Responsive Design](https://www.freecodecamp.org/news/media-query-css-example-max-and-min-screen-width-for-mobile-responsive-design/) - This article taught me how to use media queries and recommends the ideal sizes for each screen size, which I found extremely helpful.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@cvfisher](https://www.frontendmentor.io/profile/cvfisher)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)
