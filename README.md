# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
    - [The challenge](#the-challenge)
- [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
    - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- Made a semantic layout with HTML
- Practive usage of
- See hover and focus states for all interactive elements on the page

## My process

### Built with

- Semantic HTML5 markup
- BEM methodology
- CSS font face properties
- Flexbox
- Accessibility usage

### What I learned

I learned how to use semantic tags into HTML:

```html
<address class="card__location">London, United Kingdom</>
<nav aria-label="Social media links">
```

BEM usage:

```html
<div class="card__title">
  <h1 class="card__owner">Jessica Randall</h1>
  <address class="card__location">London, United Kingdom</>
</div>
<p class="card__description">
    "Front-end developer and avid reader."
</p>
```
Hover effects:
```css
.card__link:hover,
.card__link:focus-within {
    background-color: var(--green);
}

.card__link:hover a,
.card__link:focus-within a {
    color: var(--grey-900);
}
```

### Continued development

Read more about accessibility, train more usage of BEM.

### Useful resources

- [BEM methodology](https://en.bem.info/) - Resource about how to use Block-Element-Modifier.
- [MDN: Accessibility on the web](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Accessibility) - Brief introduction into accesibility by MDN

### AI Collaboration

- I used GitHub Copilot for recomendation and advices
- Asked questions about an accessibility and how better to do hover effects

## Author

- Frontend Mentor - [@DavydIkkes](https://www.frontendmentor.io/profile/DavydIkkes)
