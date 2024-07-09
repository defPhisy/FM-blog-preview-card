# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page


##

![](./assets/images/solution-screenshot.jpeg)

- Live Site URL: [Github Page](https://defphisy.github.io/FM-blog-preview-card)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

Improved my css and html skills:
- improved css-reset knowledge and created an separate css-reset file
- used `@fontface` to load local fonts
- changed my class writing from `camelCase` to `something-better-to-read`
- no more fixed fonts with `px`, hello `rem` 
- used .gitignore and and created .prettierignore to ignore formatting the new css-reset.css. Prettier listed all selectors among each other what was terrible for good reading.

Before (prettier standard formatting):
```css
h1,
h2,
h3,
h4, 
button,
input,
label {
  line-height: 1.1;
}
```
After (much nicer):
```css
h1, h2, h3, h4, 
button, input, label {
  line-height: 1.1;
}
```
