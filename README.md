# Frontend Mentor - Workit landing page solution

This is a solution to the [Workit landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/workit-landing-page-2fYnyle5lu)

### Table of contents 

- [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
- [My process](#my-process)
    - [Built with](#built-with)
    - [Interesting solutions](#interesting-solutions)
    - [Tests performed](#test-performed)
- [Author](#author)

## Overview

### Screenshot

![](./screenshot.png)

### Links

Live Site URL: [GitHub Pages]()

## My process

### Built with

- Semantic HTML 5 markup
- CSS logic properties
- Mobile-first workflow
- Flexbox
- RWD
- Sass
- BEM
- Accessibility

### Interesting solutions

For this and other challenges, I write a mixin in SASS to help me calculate clamp() function. Thes mixins can calculate clamp() using px, rem or Sass variables.

```
$text-preset-1: (
    font-size: (
        font-size-1: (fs: 3rem, vw: $viewport-mobile),
        font-size-2: (fs: 3.75rem, vw: $viewport-tablet),
        font-size-3: (fs: 5rem, vw: $viewport-desktop)
    ),
    styles: (
        font-family: $font-primary,
        font-weight: 600,
        line-height: 1,
        letter-spacing: 0
    )
);
```
```
@include fluid-typography($text-preset-1);
```

### Test performed

I performed a few tests to check the correctness of my solution. To do this, I use:
- `stylelint` - to check m Scss files
- `html-validate` - to check HTML files
- `pa11y` - to check accessibility
- `lighthouse` - to check performance

## Author

- LinkedIn [KonradJam](www.linkedin.com/in/konradjam)
- X [KonradJam_](https://x.com/KonradJam_)
- Frontend Mentor [KonradJam](https://www.frontendmentor.io/profile/KonradJam)
- Codewars [KonradJam](https://www.codewars.com/users/KonradJam)
- CodePen [KonradJam](https://codepen.io/konradjam)