# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
This project is a solution to the Bento grid challenge on Frontend Mentor. The goal was to build a responsive layout using modern HTML and CSS techniques that adapts smoothly to various screen sizes. The design is inspired by the Bento grid layout style, which neatly organizes content into visually appealing sections.

By completing this challenge, I practiced creating flexible and adaptive UI designs using CSS Grid and Flexbox, while maintaining a clean and semantic HTML structure.



### The challenge

Users should be able to:

View the optimal layout for the interface depending on their device's screen size

See the content neatly arranged in a responsive grid system

Experience smooth transitions between mobile, tablet, and desktop views

Access a layout that follows the Bento-style design with aesthetic and usability in mind


### Screenshot

Here's a screenshot of the finished project:

![](./screenshot.png)


### Links

- Solution URL: https://github.com/puja-oli/bento-box
- Live Site URL: https://puja-oli.github.io/bento-box/

## My process
Built with
Semantic HTML5 for the basic structure of the page.

CSS Grid to create the responsive bento grid layout.

Flexbox for aligning and distributing content within the grid cells.

Mobile-first workflow to ensure the layout looks great on mobile devices first, then adjust for larger screens.

Git and GitHub for version control and sharing the project with others.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

During this project, I learned a lot about the following:

Responsive design: Using CSS Grid and Flexbox to ensure the layout adapts seamlessly to different screen sizes, especially the transition between desktop and mobile views.

Grid layout: I became more proficient in using CSS Grid for complex layouts like the Bento grid.

Flexibility in design tools: While designing for different breakpoints, I practiced responsive techniques with CSS.

Here’s an example of something I learned:

html

<div class="bento-grid">
  <div class="grid-item">Item 1</div>
  <div class="grid-item">Item 2</div>
</div>


```css
.bento-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1rem;
}

Continued development

In future projects, I want to continue improving in the following areas:

Enhancing accessibility (ARIA roles and landmarks)

Further improving performance and optimizations for mobile users

### Continued development

n future projects, I want to continue improving in the following areas:

CSS Grid & Flexbox: While I've gained a solid understanding of CSS Grid and Flexbox, I want to refine my skills by experimenting with more complex layouts and learning how to seamlessly combine both techniques.

Responsive Design: Though I've applied mobile-first principles here, I aim to delve deeper into responsive design, especially in managing intricate breakpoints and ensuring an optimal layout across different screen sizes and devices.

JavaScript: I want to further develop my JavaScript skills, particularly in creating dynamic, interactive elements like modals, sliders, and other UI components that can enhance the user experience.

Performance Optimization: I'm keen on optimizing websites for better performance by exploring techniques like lazy loading, image optimization, and reducing render-blocking resources to ensure fast load times.


### Useful resources

-CSS Grid Guide by MDN - This resource was incredibly helpful in understanding the fundamentals and advanced techniques of CSS Grid. I used it to implement and experiment with different grid layouts in my project.

-Responsive Web Design Basics by Google - This guide from Google is an essential resource for learning the principles of responsive design. It provides an in-depth explanation of how to create layouts that adapt to different screen sizes, ensuring a smooth user experience across all devices.


## Author

- Frontend Mentor - [@puja-oli](https://www.frontendmentor.io/profile/puja-oli)


## Acknowledgments

I'd like to thank the Frontend Mentor community for providing this excellent challenge, which allowed me to further develop my skills in CSS Grid, Flexbox, and responsive design.

Additionally, I found some great resources and tutorials throughout the process, particularly the CSS Grid documentation, which greatly helped me understand and apply the layout principles. Thanks to everyone who shared their insights and solutions in the community — you inspired me to keep learning and improving my skills.