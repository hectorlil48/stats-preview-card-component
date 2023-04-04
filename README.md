# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshots/stat-preview-screenshot.jpg)

### Links

- Live Site URL: ([https://your-live-site-url.com](https://hectorlil48.github.io/stats-preview-card-component/))

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned how to add the color overlay by using the after pseudo-element.

```css
.card-img {
    position: relative;
}

.card-img::after {
    position: absolute;
    content: '';
    height: 98%;
    width: 100%;
    left: 0;
    top: 0;
    background-color: hsla(277, 72%, 48%, 0.6);

}
```

### Continued development

I want to keep practicing with images because I was having a hard time having them fit to the container. I also want to get more practice with the after pseudo-elements.


### Useful resources

- [MDN](https://developer.mozilla.org/en-US/) - This helped me get a better understanding of the after pseudo-element.
- [Stack overflow](https://stackoverflow.com/) - I read up on how to use the after pseudo-element.


## Author

- Website - [Hector Ramirez](https://hectoramirez.com/)
- Frontend Mentor - [@hectorlil48](https://www.frontendmentor.io/profile/hectorlil48)
- LinkedIn - [Hector Ramirez](https://www.linkedin.com/in/hector-ramirez-6a6509170?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BZ%2B%2BfJbOjRIKzo64fLPbnUA%3D%3D)

