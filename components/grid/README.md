# Grid

### Blocks

| Block           | Description                                           |
| --------------  | ----------------------------------------------------- |
| grid            | Creates a grid container intended to hold grid cells. |
| gridcell        | Creates a gridcell intended to go inside a grid.      |
| gridcell-tablet | Alters the gridcell width in tablet-sized viewports.  |
| gridcell-phone  | Alters the gridcell width in phone-sized viewports.   |

> **Note:** `gridcell` blocks must be direct descendants of `grid` blocks. To nest grids, 
declare another `grid`/`gridcell` set inside of a `gridcell`.

### Grid Modifiers

| Modifier     | Description                                                                                      |
| ------------ | ------------------------------------------------------------------------------------------------ |
| flat         | Removes the gutter between cells.                                                                |
| stretch      | Stretches the grid container to compensate for the gutter.                                       |
| flat-stretch | Stretches the grid container to compensate for the gutter, and removes the gutter between cells. |

> **Note:** These modifiers must be applied to the `grid` block.

### Gridcell Modifiers

| Modifier | Description                                       |
| -------- | ------------------------------------------------- |
| 1        | Declares that the column should be 1 unit wide.   |
| 2        | Declares that the column should be 2 units wide.  |
| 3        | Declares that the column should be 3 units wide.  |
| 4        | Declares that the column should be 4 units wide.  |
| 5        | Declares that the column should be 5 units wide.  |
| 6        | Declares that the column should be 6 units wide.  |
| 7        | Declares that the column should be 7 units wide.  |
| 8        | Declares that the column should be 8 units wide.  |
| 9        | Declares that the column should be 9 units wide.  |
| 10       | Declares that the column should be 10 units wide. |
| 11       | Declares that the column should be 11 units wide. |
| 12       | Declares that the column should be 12 units wide. |

> **Note:** These modifiers must be applied to the `gridcell`, 
`gridcell-tablet`, and/or `gridcell-phone` blocks.