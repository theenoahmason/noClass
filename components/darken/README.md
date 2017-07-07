# Darken

### Blocks

| Block  | Description                                                                                                                                                      |
| ------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| darken | Creates an overlay that darkens the element it is applied to. This is useful for obfuscating an image when information is overlayed to make text easier to read. |

> **Note:** `darken` will apply `position: relative;` to all items that are direct descendants of the applied element to ensure they appear above the overlay.

### Modifiers

| Modifier | Description                                                                                              |
| -------- | -------------------------------------------------------------------------------------------------------- |
| inherit  | Declares that the background-color of the overlay should be inherited from the element it is applied to. |

> **Note:** It is suggested that when using `darken=inherit`, `bg` is also applied to control the inherited background-color. 
