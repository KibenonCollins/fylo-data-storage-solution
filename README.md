# Frontend Mentor - Fylo data storage component solution

This is a solution to the [Fylo data storage component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the site depending on their device's screen size

### Screenshot

This is the desktop view
![](./images/Desktop%20view%20.png)

This is my Mobile view
![](//images/mobile%20view.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/KibenonCollins/fylo-data-storage-solution)
- Live Site URL: [Add live site URL here](https://kibenoncollins.github.io/fylo-data-storage-solution/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

In thi section, I learned how to use before and after. I created progess bars using percentages to show progess in the storage file.
This is the code for before
```css
.storage .meter::after{
    position: absolute;
    content: "";
    height: 12px;
    width: 12px;
    top:50%;
    left: 79%;
     background: hsl(243, 100%, 93%);
    transform: translateY(-50%);
    border-radius: 50%;
    z-index: 1;
  }


```

### Continued development

I learnt and found out that I can add two background images with one on top of each other using z-index and using background position to place them in any desired position. The code
is as shown below:
```css
body{
background-image: url("./images/bg-desktop.png");
    background-position: bottom;
    background-repeat: no-repeat;

}
```
### Useful resources

- [resource 1](https://www.w3schools.com/) - This helped me for to learn about backgound image positioning.
- [resource 2](https://alvarotrigo.com/blog/progress-bar-css/) - This is an amazing article which helped me finally understand about placing bubble texts. I'd recommend it to anyone still learning this concept.



## Author

- Website - [Kibenon Collins](https://github.com/KibenonCollins)
- Frontend Mentor - [@collinskibenon](https://www.frontendmentor.io/profile/collinskibenon)




## Acknowledgments

[Lesley Kimutai](https://github.com/Leskim) ;
[Kibiwott Kosgei](https://github.com/kibiwotkosgei)

