# REACT APP- TENMA Shopping Cart solution


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
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

- First was to find the optimised way to use CSS in this project rather then using whole lot of code use specific mesurement units and also grid in it.

- Since its an react project i have faced an challange while transering data(**props**) from one components to another.

- Also managing state in react application

### Screenshot

![Product Page](./src/assets/Web%20capture_7-4-2023_181751_localhost.jpeg)


![CheckOut Page](./src/assets/Web%20capture_7-4-2023_182019_localhost.jpeg)


### Links

- Solution URL: [Git Repository Link](https://github.com/GouravRattan/Shoppig-Cart-React)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [phosphor](https://www.npmjs.com/package/phosphor-react) - Icons Family For Interfaces


### What I learned

Learn About use of Props in react applicaption 

```JavaScript 

<> export function CartItem(props) {
  const { id, productName, price, productImage } = props.data; </> 
```
```ShopContext
const { cartItems, addToCart, removeFromCart, updateCartItemCount } =
    useContext(ShopContext);
```
```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```

### Useful resources

- [React Context](https://https://www.freecodecamp.org/news/react-context-for-beginners/#:~:text=React%20context%20caveats-,What%20is%20React%20context%3F,across%20our%20components%20more%20easily..example.com) - This helped me for using React Context.


## Author

- Website - [Shopping Cart](https://github.com/GouravRattan/Shoppig-Cart-React)

- Git-Hub - [Gourav Rattan](https://github.com/GouravRattan)

## Acknowledgments

*In this project FreeCodeCamp is the best website beginners friendly learn about component and also get help from some of the YouTube Videos*


