# typesetting_on_the_web_course

## Contact

Stephen Cronin
[Senior Developer The Outline.com](https://theoutline.com)
[Personal Website](http://scoobasteve.com)
[Email - cronin4392@gmail.com](mailto:cronin4392@gmail.com)
[Twitter - @cronin4392](https://twitter.com/cronin4392)

## Lessons

- [How the browser works presentation](/presentations/how_the_browser_works/presentation.pdf)
    - How browsers work [https://codeburst.io](https://codeburst.io/how-browsers-work-6350a4234634)
- Normalizing browser differences
    - None - (http://htmlpreview.github.io/?https://github.com/cronin4392/typesetting_on_the_web_course/blob/master/lessons/reset-css/none.html) / [Code](/lessons/reset-css/none.html)
    - Reset.css - (http://htmlpreview.github.io/?https://github.com/cronin4392/typesetting_on_the_web_course/blob/master/lessons/reset-css/reset.html) / [Code](/lessons/reset-css/reset.html)
    - Normalize.css - (http://htmlpreview.github.io/?https://github.com/cronin4392/typesetting_on_the_web_course/blob/master/lessons/reset-css/normalize.html) / [Code](/lessons/reset-css/normalize.html)
- Typesetting a book
    - Designs - [Link](/designs/book)
    - Start - [Preview](http://htmlpreview.github.io/?https://github.com/cronin4392/typesetting_on_the_web_course/blob/master/lessons/book/01/index.html) / [Code](/lessons/book/01/index.html)
    - End - [Preview](http://htmlpreview.github.io/?https://github.com/cronin4392/typesetting_on_the_web_course/blob/master/lessons/book/02/index.html) / [Code](/lessons/book/02/index.html)
- Pixels vs Ems
    - tktk
- @font-face craziness - [Preview](http://htmlpreview.github.io/?https://github.com/cronin4392/typesetting_on_the_web_course/blob/master/lessons/crazy-font-face/index.html) / [Code](/lessons/crazy-font-face)
- Responsive article
    - Designs - [Link](/designs/article)
    - Start - [Preview](http://htmlpreview.github.io/?https://github.com/cronin4392/typesetting_on_the_web_course/blob/master/lessons/article/01/index.html) / [Code](/lessons/article/01)
    - Mobile layout - [Preview](http://htmlpreview.github.io/?https://github.com/cronin4392/typesetting_on_the_web_course/blob/master/lessons/article/02/index.html) / [Code](/lessons/article/02)
    - Desktop layout - [Preview](http://htmlpreview.github.io/?https://github.com/cronin4392/typesetting_on_the_web_course/blob/master/lessons/article/03/index.html) / [Code](/lessons/article/03)


## Links

### Learning

- [CSS ruleset terminology](https://css-tricks.com/css-ruleset-terminology/)
- [Tracing the history of CSS fonts](https://www.chenhuijing.com/blog/tracing-the-history-of-css-fonts/#%F0%9F%8E%AE)
- [Modern CSS explained](https://medium.com/actualize-network/modern-css-explained-for-dinosaurs-5226febe3525)
- [How browsers work](https://codeburst.io/how-browsers-work-6350a4234634)

### Tools

- [CSS Specificty Calculator](https://specificity.keegan.st/)
- [Web Safe Fonts](https://www.cssfontstack.com/)
- [CSS Support List](https://caniuse.com/)

### Inspiration

- [TypeWolf](https://www.typewolf.com/)
- [Hoverstat.es](https://hoverstat.es/)
- [Sites we like](http://www.designmadeingermany.de/sites-we-like/)
- [SiteInspire](https://www.siteinspire.com/)
- [BTS Graphic Design Students Work](http://www.btsmultimedia-prevert.fr/projets/velvetyne2015.html)

### Things to read

- [CSS Styleguide](https://css-tricks.com/sass-style-guide/)
- [A List Apart](http://alistapart.com/)
- [/r/frontend](https://www.reddit.com/r/frontend/)

### Newsletters

- [Front-end Focus](https://frontendfoc.us/)
- [Smashing Magazine](https://www.smashingmagazine.com/the-smashing-newsletter/)

### Fonts

- [Google Fonts](https://fonts.google.com)
- [Download Google Fonts](https://google-webfonts-helper.herokuapp.com/fonts/playfair-display?subsets=latin)

----------

## Quirks

- Setting all caps type
    - This can require you to "pull" the bottom up
- Having large `letter-spacing` can cause extra space on the right
- Difference between `line-height` and leading.

## Code

### Snippets

#### Center

Better box-sizing

```css
html {
  box-sizing: border-box;
}
*,
*:before,
*:after {
    box-sizing: inherit;
}
```

Responsive image

```css
img {
    max-width: 100%;
    height: auto;
}
```

Horizontal center block element

```css
.center-me-horizontally {
    display: block; /* not required */
    width: 680px; /* adjustable */
    margin-left: auto;
    margin-right: auto;
}
```

Centering children

```css
.parent {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}
```

@font-face

```css
@font-face {
    font-family: "My Font";
    font-weight: 400;
    font-style: normal;
    src: url("../fonts/myfont.woff2") format("woff2"),
         url("../fonts/myfont.woff") format("woff");
}
```
