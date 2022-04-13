# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile first work-flow

### What I learned

I learned how to section off the card to make the profile image and information display correctly without having the entire container flex and distort the image.

```html
<div class="card colton-card">
  <div class="profile">
    <div class="avatar">
      <img src="./images/image-colton.jpg" alt="image-colton" />
    </div>
    <div class="user-info">
      <p class="username">Colton Smith</p>
      <p class="user-status">Verified Buyer</p>
    </div>
  </div>
  <div class="user-feedback">
    <p>"We needed the same printed design as the one we had ordered a week prior. Not only did they find the original order, but we also received it in time. Excellent!"</p>
  </div>
</div>
```

```css
.card img {
  border-radius: 50%;
  width: 80%;
}

.profile {
  display: flex;
  align-items: center;
}
```

I learned how to stagger divs in the desktop view based on their relative locations.

```css
.rating1 {
  position: relative;
  right: 4rem;
}
```

I learned how to customize the appearance of the background image.

```css
body {
  background-image: url(./images/bg-pattern-top-mobile.svg), url(./images/bg-pattern-bottom-mobile.svg);
  background-position: left top, right bottom;
}
```

I learned how to use flexbox within a grid to make the cards appear uniform.

```css
review-cards-container {
  display: flex;
  flex-direction: row;
  grid-column: 1/3;
  height: 100%;
  margin: 0 auto;
}
```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [CC Youtube Video](https://www.youtube.com/watch?v=lXW-euZKEEs) - This helped me with designing the grid. I will use this format going forward.

## Author

- Frontend Mentor - [@adrianna-thomas](https://www.frontendmentor.io/profile/adrianna-thomas)

```

```
