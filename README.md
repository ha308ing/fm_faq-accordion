# Frontend Mentor - FAQ accordion solution

This is a solution to the [FAQ accordion challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-wyfFdeBwBz). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

### The challenge

Users should be able to:

- Hide/Show the answer to a question when the question is clicked
- Navigate the questions and hide/show answers using keyboard navigation alone
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

#### Desktop

_Expectation_

![](./design/desktop-preview.jpg)

_Result_

[![image.png](https://i.postimg.cc/NjhVLm9Y/image.png)](https://postimg.cc/4m5wSKQF)

#### Mobile

_Expectation_

![](./design/mobile-design.jpg)

_Result_

[![image.png](https://i.postimg.cc/MGHrFDg7/image.png)](https://postimg.cc/Jywqybr0)

### Links

- Solution URL: [gh repo](https://github.com/ha308ing/fm_faq-accordion)
- Live Site URL: [gh pages deploy](https://ha308ing.github.io/fm_faq-accordion/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- JavaScript

### What I learned

- Checkbox toggle isn't triggerred on label with keyboard event when input is hidden (unlike with mouse event)
- - `<dl>` - description list
  - `<dt>` - title/term
  - `<dd>` - description itself
- css `outline-color` doesn't work without `outline-style: solid` in firefox
