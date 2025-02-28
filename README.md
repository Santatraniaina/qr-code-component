# Frontend Mentor - QR code component solution

This is a MY solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

## Table of contents

- [Frontend Mentor - QR code component solution](#frontend-mentor---qr-code-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)

## Overview

### Screenshot

![](./screenshot/Frontend%20Mentor%20-%20QR%20Code%20Component.png)

### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- HTML & CSS Only

### What I learned

I have just find out that we can do nesting with CSS like with Sass or Scss


Tell me if my code is semantic or not.
```html
<body>
  <main class="qr-code-container">
    <img src="./images/image-qr-code.png" alt="QR Code" class="qr-code"/>
    <div class="qr-code-description">
      <h4>Improve your front-end skills by building projects</h4>
      <p>
        Scan the QR code to visit Frontend Mentor and take your coding skills to
        the next level
      </p>
    </main>
  </div>
</body>
```

Loot at this CSS, it is simple and readable. What do you think about it ?
```css
.qr-code-container {
  width: 260px;
  text-align: center;
  background-color: var(--white);
  padding: 1em;
  border-radius: 1em;

  img {
    width: 260px;
    height: 260px;
    border-radius: 0.5em;
  }

  .qr-code-description {
    padding: 1em;

    h4 {
      color: var(--slate-900);
    }

    p {
      color: var(--slate-500);
    }
  }
}
```

Give me some feedback.