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
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./screenshot.png)




## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties


### What I learned

This is my first porject on my own. I used it to apply the knowledge I gained from a course I took with DeveloperDirection.

I learned that at this stage I will probably not remember all the code required to link images and css scripts to the main html file. I also learned and acknowledged that using google and stackoverflow is usually a good way of finding answeres if you are stuck. I belive that overtime I will be able to memorize commands and use them off the top of my head and not waste much time trying to figure out answers to simple questions I have.


So the first thing I learned is how to import a css style into your html file.

```html
<link rel="stylesheet" href="style.css">
```
Then I learned the class command to impoirt specific styles from the css file to specfic portions of the code. For example:

```html
<p> <img src ="./images/image-qr-code.png" alt="QR Code" class="image1"></p>
```

Now Moving on to css, I was able to figure out that naming a specific style to be used on a specific element in the code requires you to put a "." before the name of the class. In the above exmple you can see the class is "image1", it looks like this in css:


```css
.image1{
    height: 200px;
    width: 200px;
    border-radius: 25px;
    margin-left: auto;
    margin-right: auto;
    display: block;

}
```
As you can see, the class is named ".image1" and translating to html you dont use the period at the begining to become just "image1"

In the above css style, I learned how to center the image relative to the body both horizontally and vertically. I used the "margin-left" and "margin-right" commands in addition to the "display: block;" command.


### Continued development

I need to continue doing more exercise to get more hands on experience in coding. This will help me build a portfolio and gain confidence in my abilities. After a few html and css exercises I will start to add JS exercises and move to react and beyond.



## Author

Abdel Fattah Ibrahim


## Acknowledgments

Developer Direction Group. The Mentors and coders in this group have been invaluable to me. Without them I wouldn't be here.
