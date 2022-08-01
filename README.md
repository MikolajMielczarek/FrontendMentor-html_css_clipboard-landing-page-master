# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

[screenshots\screenshot_desktop.jpg]
[screenshots\screenshot_mobile.jpg]

### Links

- Solution URL: [https://github.com/MikolajMielczarek/FrontendMentor-html_css_clipboard-landing-page-master]
- Live Site URL: [https://mikolajmielczarek.github.io/FrontendMentor-html_css_clipboard-landing-page-master/]

## My process

### Built with

- Semantic HTML5 markup
- BEM
- SCSS
- Flexbox
- Mobile-first workflow

### What I learned
SCSS first time, BEM one of first use.

```scss
@mixin font-paragraphs(
$family:$font-family-name-all,
$size:$font-size-paragraphs,
$weight:$font-weight-articles,
$color:$color-bgc-font-articles, $line-height:$line-height-paragraph) {
    font-family: $family;
    font-size: $size;
    font-weight: $weight;
    color: $color;
    line-height: $line-height;
 }
```

### Continued development
```use BEM
<div class="container-buttons">
          <button class="container-buttons__button container-buttons__button--first-btn">
            <a class="container-buttons__link" href="/#">Download for iOS</a>
          </button>
          <button class="container-buttons__button container-buttons__button--second-btn">
          <a class="container-buttons__link" href="/#">Download for Mac</a>
          </button>
</div>
```

### Useful resources

- [https://fontawesome.com/v5/icons/instagram?s=brands] - helped me in download icons and format them with text property.
- [https://css-tricks.com/snippets/css/a-guide-to-flexbox/]- helped me to understand more of flex-box concept
- [https://sass-lang.com/guide]- helped me to understand how to use SCSS.

## Author

- Frontend Mentor - [@MikolajMielczarek](https://www.frontendmentor.io/profile/MikolajMielczarek)