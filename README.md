# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

[Mobile view](https://github.com/rameesha0126/order-summary-component/blob/master/Mobile-view.png)
[Desktop view](https://github.com/rameesha0126/order-summary-component/blob/master/Desktop-view.png)

### Links

- Solution URL: [Solution](https://github.com/rameesha0126/order-summary-component.git)
- Live Site URL: [Live site URL](https://rameesha0126.github.io/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Float
- Mobile-first workflow

### What I learned 

-Using more than one class in an element to give common styling and unique styling at the same time. 

```html
<p class="button proceed">Proceed to Payment</p>
<p class="button cancel">Cancel Order</p>
```

```css
.button {
  width: 90%;
  border: none;
  padding: 1em;
  border-radius: 1em;
}
.proceed {
  color: hsl(225, 100%, 98%);
  background-color: hsl(245, 75%, 52%);
  margin: 1em 0 0 0;
}

.cancel {
  color: hsl(224, 23%, 55%);
  font-weight: 700;
  margin: 0 0 1em 0;
}
```

Using pseudo classes to give different styles on hover and active states. 
```css
.proceed:hover, .proceed:active {
  background-color: hsl(266, 40%, 49%);
  cursor: pointer;
}

.cancel:hover, .cancel:active {
  color: hsl(223, 47%, 23%);
  cursor: pointer;
}
```

### Continued development

-Working on box-shadow elements

### Useful resources

- [W3schools CSS Tutorial](https://www.w3schools.com/css/default.asp)

## Author

- Github - [Rameesha0126](https://github.com/rameesha0126)
- Frontend Mentor - [@rameesha0126](https://www.frontendmentor.io/profile/rameesha0126)
