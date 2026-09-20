# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Mobile preview](./screenshots/mobile-preview.jpg)
![Desktop preview](./screenshots/desktop-preview.jpg)

### Links

- Solution URL: (https://github.com/sujinch/blog-preview-card-main.git)
- Live Site URL: (https://sujinch.github.io/blog-preview-card-main/)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned

I learned a lot from this project, not only about writing code, but also about choosing better and more modern approaches.

One of the main things I learned is that it’s important to think beyond "does this work?" and also consider "is this the best practice?" For example, I used to rely on float for layouts, but through this project I learned that Flexbox is a more modern, flexible, and reliable approach for creating layouts.

I also learned about clamp(), which I found really useful for making text responsive. It allows the font size to adjust depending on the screen size without needing to use media queries for every breakpoint.

Another thing I learned was that HTML elements should be chosen based on their purpose. At first, I used a <button> for the "Learning" category because I wanted it to look like a button. I later realized that since it isn't actually an interactive button, a <span> was more appropriate, and I could still style it to look the way I wanted.

Overall, this project helped me understand that good web development is not just about making something work, but also about writing cleaner, more appropriate, and more maintainable code.

html code I'm proud of
```html
<span id="category">Learning</span>
```
css code I'm proud of
```css
font-size: clamp(0.75rem, 0.693rem + 0.244vw, 0.875rem);
```

### Continued development

I definitely need to learn more about CSS Grid and Flexbox so I can become more comfortable with creating responsive and well-structured layouts.

I also want to keep improving at choosing HTML elements based on their purpose and semantic meaning, rather than choosing them based only on how I want them to look.

### AI Collaboration

Describe how you used AI tools (if any) during this project. This helps demonstrate your ability to work effectively with AI assistants.

- Tools I used: ChatGPT, Google Gemini, GitHub Copilot.

- GitHub Copilot:
 I mostly used GitHub Copilot when I got stuck or needed help debugging something. It was also useful for giving me ideas and pointing me toward approaches that I hadn't thought about before. For example, it helped me realize that Flexbox would be a better choice than float for my layout, and that using a <span> instead of a <button> made more sense for the "Learning" category. I found Copilot especially helpful because it didn't just help me fix problems, but also gave me opportunities to learn why some solutions were better than others.

- Google Gemini:
I used Gemini mainly when I forgot the syntax for something or wasn't sure how to do something. I also used it to explain some of the suggestions or remarks from Copilot when I didn't fully understand them. It was helpful to have another way to understand the code instead of just copying a solution. It helped me understand what I was doing and why a particular approach might work.

- ChatGPT
I used ChatGPT mainly to help me make my README more professional and well-structured. I provided my own ideas and what I learned from the project, then used ChatGPT to improve the wording and organize everything in a clearer way. This helped me present my work and learning experience in a way that is easier to read while still keeping my own ideas and experience.


## Author
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
