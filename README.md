# Make It Real Onion Hater NAME OF THE PROJECT

This is a solution to the Onion Hater project of the Make It Real course.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- Write in a textarea anything you want but, if you write 'cebolla' in upper or lower case then appears an alert saying "ODIO LA CEBOLLA"

### Screenshot

<img width="503" alt="image" src="https://github.com/Camilo-Suarez98/onion-hater/assets/68169750/ee320ed4-2f2a-48b7-98a5-c189adbcb649">

<img width="506" alt="image" src="https://github.com/Camilo-Suarez98/onion-hater/assets/68169750/60d1709f-4361-4d00-ad0a-3c5dab3a4ae4">

<img width="480" alt="image" src="https://github.com/Camilo-Suarez98/onion-hater/assets/68169750/c932403f-54dc-4531-97d4-c54835dae9a3">

## My process

### Built with

- React + Vite
- Javascript

### What I learned

I learn about the events on React and how i can get a value from an element, in this case i used an arrow function called handleChange

```html
<textarea onChange={handleChange} name="onion" id="text" cols="30" rows="10" />
```
```js
const handleChange = (e) => {
  const text = e.target.value

  if (text.toLowerCase().includes('cebolla')) {
    alert('ODIO LA CEBOLLA')
  }
}
```

## Author

- Website - [Camilo S](https://camilo-suarez98-github-io.vercel.app/)


## Acknowledgments

Thanks to Make It Real team to teach me about this and all about React
