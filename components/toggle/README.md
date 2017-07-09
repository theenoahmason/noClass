# Toggle

### Blocks

| Block          | Description                                                                                                                                                              |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| toggle-trigger | Creates a toggle trigger that will show the section directly after it, if it has the `toggle-target` attribute. Must be an input of `type="checkbox"` or `type="radio"`. |
| toggle-target  | Creates a toggle target that will show if the `toggle-trigger` before it is checked.                                                                                     |

> **Note:** `toggle-trigger` must be used on inputs of `type="checkbox"` or `type="radio"`, and must be immediately followed in the DOM by an element with `toggle-target`. 
> The `toggle-trigger` must also have an `id` attribute. Once set up, use a `label` element with a `for` attribute with the input's `id` to trigger it with no javascript needed.
> Using a radios with the same `name` attribute will behave like tabs/accordions, where only one of the set can be checked at any given time. 

### Toggle Trigger Modifiers

| Modifier | Description                                                                                                                  |
| -------- | ---------------------------------------------------------------------------------------------------------------------------- |
| desktop  | Declares that the toggle target should only work on desktop-width viewports, and should stay open on mobile-width viewports. |
| mobile   | Declares that the toggle target should only work on mobile-width viewports, and should stay open on desktop-width viewports. |

> **Note:** When using `toggle-trigger="mobile"` or `toggle-trigger="desktop"`, using `remove="mobile"` and `remove="desktop"` respectfully on 
> `toggle-trigger` and `toggle-target` blocks can show/hide either for desired layout.