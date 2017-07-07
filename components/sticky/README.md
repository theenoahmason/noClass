# Sticky

### Blocks

| Block  | Description                                                                                                                                                                        |
| ------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| sticky | Makes an element stick inside of it's parent, according to the modifier. If no modifier is set, it is expected that a CSS `top`, `bottom`, `left`, or `right` value is set for that element. |

> **Note:** This component uses CSS sticky positioning. As such, the sticky item's parent element cannot have overflows hidden.

### Modifiers

| Modifier | Description                                                                                                                                 |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| top      | Declares that the element should be stuck to the top of the viewport when scrolling vertically, as long as it's in it's parent element.     |
| bottom   | Declares that the element should be stuck to the bottom of the viewport when scrolling vertically, as long as it's in it's parent element.  |
| left     | Declares that the element should be stuck to the left of the viewport when scrolling horizontally, as long as it's in it's parent element.  |
| right    | Declares that the element should be stuck to the right of the viewport when scrolling horizontally, as long as it's in it's parent element. |

> **Note:** All modifiers will set the pixel distance from the edge to 0px, this can be overridden by inline styles on the element (`style="top:16px;"`), or by CSS stylesheet.