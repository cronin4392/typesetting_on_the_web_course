# CSS Font Properties

| Property         | Units                                           | Description                     |
| ---------------- | ----------------------------------------------- | ------------------------------- |
| `font-size`      | `px` `em` `rem` `vw` `vh`                       | Size of the font                |
| `line-height`    | `px` `em` `rem` `unitless`                      | Leading / spacing between lines |
| `font-weight`    | `normal` `bold` `100` `200` `300` … `800` `900` | Weight of the font.             |
| `font-style`     | `normal` `italic`                               | Choose Normal or Italic.        |
| `text-transform` | `none` `uppercase` `lowercase`                  | Capitalization.                 |
| `letter-spacing` | `px` `em` `rem`                                 | Space between letters           |
| `word-spacing`   | `px` `em` `rem`                                 | Space between words             |

notes:

- `line-height` differs from leading. In design leading will not effect 1 line of text. `line-height` however will change how 1 line of text is rendered.
- To derive `letter-spacing` from design programs take the value and divide by 1000 and set that value in ems.
  - 40 -> `letter-spacing: 0.04em`