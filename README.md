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

- Solution URL: [Add solution URL here](https://github.com/AnakonStar/results-summary-component-main)
- Live Site URL: [Add live site URL here](https://anakonstar.github.io/results-summary-component-main/)

## My process

### Built with

- Basic HTML tags
- Semantic HTML
- @media-screen for all types of view
- Basic CSS

### What I learned

I think it might be best practices about Semantic HTML, basically it organizes HTML tags better, not just stuffing them with classes.

Do this:

```html
<section class="memorybg">
  <div>
    <object data="./assets/images/icon-memory.svg" width="20px" height="20px"></object>
    <h2 class="memory">
      Memory
    </h2>
  </div>
  <div>
    <h2>92 <span>/ 100</span></h2>
  </div>
</section>

Instead of this:

<div class="memorybg">
  <div class="section">
    <object data="./assets/images/icon-memory.svg" width="20px" height="20px"></object>
    <h2 class="memory">
      Memory
    </h2>
  </div>
  <div class="values">
    <h2>92 <p>/ 100</p></h2>
  </div>
</div>
```

I know it seems like this doesn't make a difference, but with a large amount of code, this can be very useful.
(NOTE: You must be thinking why I put a class in a section, it's because, if you look at my code, you'll see that there are 4 types of summary option, and each one has its own color. And just for explanation , I used div inside section, because section has its unique style and div, it's just cleaner in css code)

### Continued development

I just started from the last project uploaded, learning about ReactJS, and it's kind of similar to React-Native (I've been using React-Native for 2 years now to produce applications based on the Android operating system), same base and uses, but with HTML tags and CSS for style sheet. So I think I can go even further and make many lighter and better sites.

### Useful resources

- [Example resource 1](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure) - This blog just taught me the correct way to use semantic HTML to structure websites better

## Author

- LinkedIn - [Enzo Santana](https://www.your-site.com)
- GitHub - [AnakonStar](https://github.com/AnakonStar)
- Frontend Mentor - [@AnakonStar](https://www.frontendmentor.io/profile/AnakonStar)
- Workana - [Enzo Santana](https://www.workana.com/freelancer/4c2cdd8b9e92d8b32763edc91d6cde18)
