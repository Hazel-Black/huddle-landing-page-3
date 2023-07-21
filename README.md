
# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
Im revisting this challange that I did over a year ago, I have gain alot of knowledge since then so I figured this would be fun. 
### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](images/Screenshot%202023-07-21%20at%208.31.42%20AM.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [huddle-landing-page-3](https://hazel-black.github.io/huddle-landing-page-3/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Im very proud of the nesting i did with this project. it became very usuful when styling the icons later on. 
```html
 <div class="icons">
        <div class="facebook">
          <i class="fa-brands fa-facebook-f"></i>
        </div>
        <div class="twitter">
          <i class="fa-brands fa-twitter"></i>
        </div>
        <div class="insta"><i class="fa-brands fa-instagram"></i></div>
      </div>
```
Im also ver prouid of the work I did on the background image (destop version). It took alot of time to find the perfect resolution for my problems. I stuggled with tons of overflow, side scrolling ect. but I was able to resolve my issues with this code.
```css
@media (min-width: 724px) {
  body {
    background-image: url(images/bg-desktop.svg);
    background-position: left -4em bottom -2.5em;
    background-size: cover;
    text-align: left;
    width: fit-content;
    max-width: 100%;
  }
}
```



### Continued development
I'm currently looking forward to working on new projects and playing around with grid instead of flexbox. this was a great project to revist for sure! 

### Useful resources

- [CSS Icons- W3Schools](https://www.w3schools.com/css/css_icons.asp) - This helped me to learn about using font awesome icons.
- [Font Awesome](https://fontawesome.com/) - This is an amazing resources for icons, I used this site for all the icons I used. 
## Author

- Frontend Mentor - [@Hazel-Black](https://www.frontendmentor.io/profile/Hazel-Black)
- LinkedIn - [@HazelBlack](www.linkedin.com/in/hazel-black-a40315237)

