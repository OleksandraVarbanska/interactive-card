# Interactive card details form solution

This is a solution to the [Interactive card details form challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/interactive-card-details-form-XpS8cKZDWw). 

<img height="550px" width="500px" src="design/desktop-design.jpg"/>

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

- Fill in the form and see the card details update in real-time
- Receive error messages when the form is submitted if:
  - Any input field is empty
  - The card number, expiry date, or CVC fields are in the wrong format
- View the optimal layout depending on their device's screen size
- See hover, active, and focus states for interactive elements on the page

### Links

- Live Site URL: [Interactive card details form solution](https://oleksandravarbanska.github.io/interactive-card/)

## My process

### Built with

- Semantic HTML5 markup- `index.html`
- The main styles file is `styles.css`.
- The layout is implemented using Flexbox

### What I learned
While working on the project, I learned the basic principles of HTML and CSS layout. <br></br>The main focus was on creating an adaptive layout using Flexbox.

**Key skills:**

***HTML: semantic markup, content structuring.***

  ```html
 <div class="data">
        <label for="card_number">Card Number</label>
        <input 
        type="text" 
        pattern="[0-9]{16}"
        placeholder="e.g. 1234 5678 9123 0000" 
        id="card_number" 
        name="card_number" 
        oninput="this.value=this.value.replace(/\D/g, '')"
        title="Enter the 16-digit card number"/>
      </div>
```
            
***CSS: applying styles, working with colors, fonts, indents.***

```css
input::placeholder {
  font-size: 18px;
  line-height: 23px;
  color: #21092f;
  mix-blend-mode: normal;
  opacity: 0.25;
}
```

***Flexbox: creating adaptive layouts, element alignment, space management.***

```css
.flx {
  display: flex;
  align-items: center;
  justify-content: center;
}
```

### Continued development

- Optimize the page for mobile devices
- Perform a switch to a dark theme
- Practice manipulating the DOM

### Useful resources

- [MDN](https://developer.mozilla.org/en-US/) - It helped me to familiarize myself with the theory HTML, CSS and other useful tools.
- [learningtogetherua](https://www.youtube.com/@itmentor) - The lecturer from whom I took a course on the theory and practice of HTML, CSS. I'm still learning - mastering JS.

## Author

- Frontend Mentor - [Oleksandra Varbanska](https://github.com/OleksandraVarbanska)
- Telegram - [Oleksandra Varbanska](https://t.me/nemin_na_ari)

