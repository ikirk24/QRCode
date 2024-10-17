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
  I made a simple QR code website with HTML and CSS. To complete the project I had to make a square with divs and put it into the middle of the screen to use as the base for the image and text. I used the Figma file to exact the width, height, padding, and colors of all of the elements which made it so much easier instead of estimating what to use. I'm not entirely adept at CSS so I usually learn along the way of making things but this QR code didn't turn out to be much of a challenge. 

### Screenshot
![Qr Code](<Qr Code SS.png>)

### Links

- Solution URL: [Solution](https://github.com/ikirk24/QRCode/blob/main/style.css) && (https://github.com/ikirk24/QRCode/blob/main/index.html)
- Live Site URL: [Live Site](https://ikirk24.github.io/QRCode/)

## My process
  I started with some HTML to make some divs that would later become my box models in CSS. I've learned to think of websites in terms of boxes so I made one big container that is the parent to every element on the page and then broke them down into smaller containers. There's a container for back drop of the QR code and text. Then inside that box there are boxes that house the image and other boxes that hold the text. Using the Figma files made it pretty easy for me to make the QR code look almost identical to the example picture given before hand. 

### Built with

- HTML
- CSS

### What I learned

I learned/relearned a few things during this project. The first one was that I needed to use {position: absolute;} in CSS on the main box that houses the image and text in order to manipulate it into fitting in the middle of the screen. The second thing I learned was in order to curve my images I had to actually attach the image to a square and use {overflow: hidden;} on that square. Then I used border-radius to curve it. 

### Continued development

I want to make really cool looking websites and apps in the future. I'm not too sure how to make responsive websites so I hope to do that in the future. 

### Useful resources

- [Resource 1](https://css-tricks.com/) - This helped me to center my boxes, it has a bunch of easy to access and understandable guides.
- [Resource 2](https://stackoverflow.com/) - This is a great website for questions that I had. I didn't have to actually ask anyone questions though, most of the time the question had been asked by someone else in the past and I could just use the answer they gave them. 

## Author

- Frontend Mentor - [@ikirk24](https://www.frontendmentor.io/profile/ikirk24)

## Acknowledgments

I did this on my own with the help of a few websites I listed above. 