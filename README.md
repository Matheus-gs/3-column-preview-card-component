# Frontend Mentor - 3-column preview card component solution 👨🏽‍💻

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

#### This project was really fun to do and I was able to learn a lot more about my knowledge of CSS


## The challenge

#### The challenge was to create some cards and place them side by side in three columns in the desktop versions. And in the mobile version, the cards must be positioned one below the other.

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements


### Screenshot

### Desktop Version
![Desktop Version](https://user-images.githubusercontent.com/54650216/114411379-812a0300-9b82-11eb-8ed6-807dd2d87761.png)

### Mobile Version (Iphone X)
![Mobile (Iphone X) Version](https://user-images.githubusercontent.com/54650216/114411504-9d2da480-9b82-11eb-8fa3-aad2905a9129.png)![image](https://user-images.githubusercontent.com/54650216/114413403-550f8180-9b84-11eb-8c8e-ba9f61c4ffa9.png)


### Links

- Solution URL: [Project Repository](https://github.com/Matheus-gs/3-column-preview-card-component)
- Live Site URL: [Project on GitHub Pages](https://matheus-gs.github.io/3-column-preview-card-component/)

## My process 

### First Step (preparing the structure and identifying the elements)

Create a div and place the contents of the card (images, title, some text and the button)

![image](https://user-images.githubusercontent.com/54650216/114414543-49708a80-9b85-11eb-8714-eea0cdabd8c6.png)

Repeat the process of creating and renaming the other divs (cards) with different names to help us on css

![image](https://user-images.githubusercontent.com/54650216/114415310-f3e8ad80-9b85-11eb-8f39-1229fc62612b.png) ![image](https://user-images.githubusercontent.com/54650216/114415394-0531ba00-9b86-11eb-8b16-5449820a0e22.png)

Then create a footer and place the assignment divs inside it

![image](https://user-images.githubusercontent.com/54650216/114415586-33af9500-9b86-11eb-8705-3db6aba37acd.png)

Put all the elements (#first, #second, #third, __card) inside a div (#cards), this will help us to place the cards side by side and in the center of the screen using css

![image](https://user-images.githubusercontent.com/54650216/114418305-c4877000-9b88-11eb-9734-b1525ce85d4c.png)

### Second Step (Adding CSS)

I start my css code by redefining some properties, importing external sources and removing the scroll bar (Note: removing the scroll bar is optional, I don't particularly like the scroll bar so I usually take it out on all my web projects)

![image](https://user-images.githubusercontent.com/54650216/114425821-d0c2fb80-9b8f-11eb-8acd-03fe1c78cf6a.png)

Now we will insert some css in the div #card these properties will be responsible for aligning the elements to the center and assist in responsiveness using the flexbox
  
![image](https://user-images.githubusercontent.com/54650216/114427518-88a4d880-9b91-11eb-8236-79b10396ae36.png)

Here we will define the properties of each card (size, colors, padding and alignment)

![image](https://user-images.githubusercontent.com/54650216/114428227-4e880680-9b92-11eb-85d1-bf0c41a3f6cb.png)

After defining the general properties of the cards, we will apply the particular properties, that is, the unique characteristics of each card (background colors and font colors basically)

![image](https://user-images.githubusercontent.com/54650216/114428612-c7875e00-9b92-11eb-8a38-f22a310d3ce8.png) ![image](https://user-images.githubusercontent.com/54650216/114428673-db32c480-9b92-11eb-8d04-2cb9158c4d5f.png) ![image](https://user-images.githubusercontent.com/54650216/114428707-e4bc2c80-9b92-11eb-8f92-c6a72156ee2e.png)

Here we will configure the general properties of the content that will be inside each card, these properties are practically the same on each card, so I defined them with the names of the tags (however if you have more elements like these on your page it is recommended that you define them with different names using class, ID, etc.)

![image](https://user-images.githubusercontent.com/54650216/114430063-695b7a80-9b94-11eb-8fc6-3f89dad06555.png)

Defining footer characteristics

![image](https://user-images.githubusercontent.com/54650216/114430329-b4758d80-9b94-11eb-93d0-65369c9f744d.png)

### Third and last step (Creating the transition to the mobile version)

In this step we will use media queries to change the css properties

![image](https://user-images.githubusercontent.com/54650216/114430818-349bf300-9b95-11eb-9a29-c86be92bffbc.png)

Basically, we changed the size of some elements and added a scroll effect using the properties: scroll-snap-type and scroll-snap-align

#### *That's all, folks!*


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Google Fonts

### What I learned

In this project, in addition to reinforcing knowledge, I also learned how to use some flexbox properties like flex-wrap and how to make scrolling effects using css


### Useful resources

google fonts that were used in this project:
  - [Montserrat](https://fonts.googleapis.com/css2?family=Montserrat:wght@300&display=swap)
  - [Bebas](https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap)


## Author

- Website - [Matheus Gomes](https://www.your-site.com)
- Frontend Mentor - [@Matheus-gs](https://www.frontendmentor.io/profile/yourusername)


## see the project on GitHub Pages [Project](https://matheus-gs.github.io/3-column-preview-card-component/)

