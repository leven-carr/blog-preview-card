# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

I started by creating my styles.css file and linking it to the html; I also linked the font. In styles.css, I created a section for the color variables, did a universal reset, and brought over the provided .attribution styles (and removed the style tag from my html).

Next I worked on the html: I created a main element to hold the content, and nested a div within that to use to position the blog preview card, which is a section element. Inside the card, I created 4 divs in order to use flexbox to arrange the content. The first flex-container holds the image; the second holds the "Learning" topic and the publication date; the third holds the title of the article and the snippet paragraph; the last one holds the author's picture and name. Those four divs, as well as the outermost div, all have the class flex-container so that I didn't have to rewrite the flexbox rules for each of them. They also each had another class so that I could write the rules specific to each of them.

With the flexbox skeleton set up I created the various elements (img, p, p, h1, p, img, p) and put them in their respective divs and filled them in with the corresponding content.

At this point I moved onto the CSS; I started by setting the background of the body, wrote the broad flex-container rules, then styled the card itself before moving onto the elements within the card, working from top to bottom. I skipped setting the margins until after I had finished applying font sizes, font weights, line heights, etc. so that I could see what the elements looked like before I spaced them. Then I went back and added bottom margins where necessary to space the elements accordingly (also added a right margin to separate the author's picture and name).

The last couple things I did were to go back and nest an a tag inside the h1, around the blog post title. Then I set the :hover and :focus styles of the link. I also went back and changed the font-weight of the body to 500 for the other elements to inherit (unless they had a font-weight otherwise applied), to better match the style guide.

### Built with

HTML and CSS (including flexbox); no CSS frameworks or JS

### What I learned

This was really good practice for me using flexbox, and also using custom CSS variables. I feel pretty good about how I worked out the spacing; I'm not sure if it was the cleanest way to do it but leaving the margins until near the end felt like an efficient way for me space out the elements, rather than guessing/checking/fixing as I went.

### Continued development

In the future I want to get better at adjusting things for scalability and responsiveness on different screen sizes.

## Author

- Frontend Mentor - [@leven-carr](https://www.frontendmentor.io/profile/leven-carr)
- GitHub - [@leven-carr](https://github.com/leven-carr)
