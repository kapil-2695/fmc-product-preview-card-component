# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [My favourite code](#my-favourite-code)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### Screenshot

<img src="./screenshots/desktop-screenshot.jpg" alt="Desktop screenshot" width="650" />
<div style="display: flex; gap: 0.5rem;">
  <img src="./screenshots/mobile-screenshot.jpg" alt="Mobile screenshot" width="180" />
  <img src="./screenshots/active-screenshot.jpg" alt="Active screenshot" width="180" />
  <img src="./screenshots/tablet-screenshot.jpg" alt="Tablet screenshot" width="290" />
</div>


### Links

- Solution URL: [Product Preview Card Component Solution](https://github.com/kapil-2695/fmc-product-preview-card-component)
- Live Site URL: [Live site - Product Preview Card Component](https://kapil-2695.github.io/fmc-product-preview-card-component)


## My process
  
### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid and Flexbox
- CSS media query


### What I learned

- I learned to switch between CSS Grid and Flexbox using media query based on viewport size.
- I learned to make the layout responsive.
- I learned to switch between mobile and desktop versions of image using media query.


### My favourite code
```css
main {
    display: flex;
    flex-direction: column;
    background-color: var(--clr-white);
    max-width: 21.875rem;
    width: fit-content;
    margin: 2rem 0.75rem;
    border-radius: 0.5rem;
}
```

switched to:

```css
@media (min-width: calc(37.5rem + 1.5rem)) {
    main {
        display: grid;
        grid-template-columns: 1fr 1fr;
        max-width: 37.5rem;
    }
}
```
- **+1.5rem** in the media query accounts for the margins, hence I have mentioned it separetely.


### Useful resources

- [Learn CSS - web.dev](https://web.dev/learn/css/) - This helped me with CSS code.


## Author

- Frontend Mentor - [@kapil-2695](https://www.frontendmentor.io/profile/kapil-2695)

<br />

[Back to table of contents](#table-of-contents)

[Back to Top](#frontend-mentor---product-preview-card-component-solution)
