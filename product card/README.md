# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#Product Card Design)
  - [The challenge](#Responsiveness)
  - [Screenshot](#screenshot)
  - [Built with](HTML&CSS)
  - [What I learned](Responsive-Design)
  - [Continued development](#continued-development)
  - [Useful resources](Css-Tricks)
  - [Author](Fortune)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
- The Structure
- Stying for the mobile
- Adding Media Queries to make it look good on desktop also
- Added finishing touches

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Media Queries
- Mobile-first workflow

### What I learned

While working on this project i found out about the useful html markup calle picture and its ability to change the source of an image depending on the device screen size.

### Exapmple Code

```html
  <picture>
    <source srcset="images/image-product-desktop.jpg" media="(min-width:720px)">
    <source srcset="images/image-product-mobile.jpg" media="(max-width:720px)">
    <img src="images/image-product-desktop.jpg" alt="picture of a bottle of perfume" class="p-img">
  </picture>
```

### These are some of the important code needed to achieve success in creating this beautiful design.

```html
  <picture>
    <source srcset="images/image-product-desktop.jpg" media="(min-width:720px)">
    <source srcset="images/image-product-mobile.jpg" media="(max-width:720px)">
    <img src="images/image-product-desktop.jpg" alt="picture of a bottle of perfume" class="p-img">
  </picture>
```
```css
.p-desc {
  line-height: 1.8rem;
  font-size: 1.2rem;
  font-weight: 500;
  color: hsl(228, 12%, 48%);
}
```

### Continued development

I want to focus more on css and and use the concepts in which i have learnt from it to create responsive and beautiful designs responsive design skills. At the moment i am quite comfortable using flex-box and grid to create responsive and beautiful layouts.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/Fortune-Codes15)
- Twitter - [@FortuneCodes](https://www.twitter.com/https:/fortune_codes);
- LinkedIn - [Fortune Foluso](https://www.linkedin.com/in/fortune-foluso-45583b358/);