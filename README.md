

# Front End Masters Course - CSS foundations

- I worked through and completed Front End Masters ‘Getting Started With CSS’ course, which was a great way to cement and refresh my CSS fundamentals. I got some reps in with Grid, Flexbox and Media Queries as well as learning a few new tricks such as attribute selectors and the ‘order’ property. The course project was to create a portfolio website, but as I already have one, I created one for the legend that is Bob The Builder, in the hopes of getting him some work and making him relevant once more. You can check out the website below:

## Takeaways and new tricks learned:

- border-box model to use in all CSS:

```
html {
  box-sizing: border-box;
}
*,
*::before,
*::after {
  box-sizing: inherit;
}

```
- within page content leave links underlined for accessibility reasons. need to ways of identifying links as 10% of users are color blind. Ok to remove text decoration in the navbar though as links are expected here.
- If you use `display:block;` on an anchor tag it makes the link fill the full clickable area instead of just the text and thus makes it easier to click. Useful trick for navbars
- Font Awesome is awesome.
- My first time using `Aria-hidden`. useful for accessibility features.
- first time using attribute selectors. Can be handy in specific situations.

```
nav [class*='fa-'] {
  font-size: 120%;
  color: var(--aqua);
}

```

`order` property for CSS grid and flexbox is very useful. 
