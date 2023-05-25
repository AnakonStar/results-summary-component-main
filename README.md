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

## Overview

### Screenshot

![Desktop View](./images/desktop.jpg)
![Mobile View](./images/mobile.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- SASS for better style overview
- Basic HTML tags
- Basic CSS

### What I learned

The most valueble element that I used in this project was Reponsive Pages, that basically let you choose a different style to the page, based on the viewport, be it Mobile or Desktop.

Like the example bellow:

Mobile

```css
.qr-container { 
  width: 85%;
  padding: 18px; 
  display: flex; 
  border-radius: 5%; 
  background-color: hsl(0, 0%, 100%); 
  flex-direction: column; 
  align-items: center; 
}

Desktop

@media screen and (min-width: 375px) {
  .qr-container {
      width: 16%;
  }
}
```

This will very helpful in the next time!

### Continued development

Maybe, learn more about other ways to do a website, like using React.js, Python, PHP, that I alredy used, but don't go much futher. Other thing will be about Clean Code, I want to study about, and implement in my future projects

### Useful resources

- [Example resource 1](https://www.youtube.com/watch?v=gRIWFYRaVto) - This video from Hostinger Brasil (yes, I'm brazilian) help me to, like a said in What I learned, to understand more about reponsive pages and how to implement them.
- [Example resource 1](https://elementor.com/help/whats-the-difference-between-px-em-rem-vw-and-vh/#:~:text=VH%20is%20useful%20for%20creating,to%20viewport's%20width%20or%20height.) - This article, teach me about some differences about measurement units in CSS.

## Author

- LinkedIn - [Enzo Santana](https://www.your-site.com)
- GitHub - [AnakonStar](https://github.com/AnakonStar)
- Frontend Mentor - [@AnakonStar](https://www.frontendmentor.io/profile/AnakonStar)
- Workana - [Enzo Santana](https://www.workana.com/freelancer/4c2cdd8b9e92d8b32763edc91d6cde18)
