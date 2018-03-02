# typesetting_on_the_web_course

## Lessons

- [How the browser works](tktk.com)
- Normalizing browser differences
    - [None](/lessons/reset-css/none.html)
    - [Reset.css](/lessons/reset-css/reset.html)
    - [Normalize.css](/lessons/reset-css/normalize.html)
- Typesetting a book
    - [Start](/lessons/book/start.html)
    - [End](/lessons/book/end.html)


## Links

[CSS Styleguide](https://css-tricks.com/sass-style-guide/)

## Quirks

- Setting all caps type
    - This can require you to "pull" the bottom up
- Having large `letter-spacing` can cause extra space on the right
- Difference between `line-height` and leading.

## Code

### Snippets

#### Center

Block element

```css
display: block; /* not required */
width: 680px; /* adjustable */
margin-left: auto;
margin-right: auto;
```

Centering children

```css
display: flex;
flex-direction: column;
align-items: center;
justify-content: center;
```
