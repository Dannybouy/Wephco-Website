Wephco Real Estate Website Project

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

![Screenshot 2022-08-27 at 11-20-37 Wephco](https://user-images.githubusercontent.com/65716830/187026180-d01cb8aa-9587-4882-a35b-28cf655d9a22.png)

![Screenshot 2022-08-27 at 11-29-05 Wephco](https://user-images.githubusercontent.com/65716830/187026268-40cfa63b-17f8-49ea-a705-76393b51ec76.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox
- Desktop first workflow
- Vanilla JavaScript

### What I learned

Some Code Snippets from the project

```html
<main class="main-section">
  <section class="main__section-1">
    <h2 class="main__header">Buy, Rent or Sell properties in Abuja</h2>
    <p class="main__text">
      Let us take the hassle of house hunting off your shoulder for a small fee
    </p>
    <a class="main__btn">Find a property</a>
  </section>
  <section class="main-section-2">
    <img
      class="main-img"
      src="Frame 163/Frame 163.svg"
      alt="Main section image"
    />
  </section>
</main>

<section class="companies">
  <div class="company_title">Trusted By Reputable Nigerian Companies</div>
  <div class="list__of_companies">
    <img src="designassets/Betway Logo 1.svg" alt="Betway logo" />
    <img src="designassets/Business Day Logo 1.svg" alt="Business day logo" />
    <img src="designassets/Busha Logo 1.svg" alt="Busha logo" />
    <img src="designassets/Cowrywise Logo 1.svg" alt="Cowrywise logo" />
    <img src="designassets/Bolt Logo 1.svg" alt="Bolt logo" />
  </div>
</section>
```

```css
@media (max-width:900px) {
   .hamburger{
       display: block;
   }

   .navbar {
       display: block;
       position: fixed;
       left: 0;
       top: 0;
       height: 100vh;
       width: 50%;
       z-index: 2;
       background-color: #fff;
       transform: translateX(-100%);
       transition: transform .5s ease-in-out;
   }

   .open-nav {
    transform: translateX(0%);
    }

    .close {
        float: right;
        margin: 2em;
        width: 2.5em;
        display: block;
    }
```

## Author

- Frontend Mentor - [@Dannybouy](https://www.frontendmentor.io/profile/Dannybouy)
- Twitter - [@Dan_d_man](https://twitter.com/IamDannybouy20)
- LinkedIn - [Daniel](https://www.linkedin.com/in/daniel-okpara/)
