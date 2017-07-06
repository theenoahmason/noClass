# Field

### Blocks

| Block          | Description                                                                                       |
| -------------- | ------------------------------------------------------------------------------------------------- |
| field          | Creates a field for use with forms, containing a label, input, and optional error.                |
| field-error    | Creates a field error to be shown if the field's input is invalid.                                |

> **Note:** The field error should be placed directly after the input element.

### Nodes

| Nodes        | Description                                                                             |
| ------------ | --------------------------------------------------------------------------------------- |
| label        | Defines the field label.                                                                |
| input/select | Defines the field input. This can be an input element of any type, or a select element. |

> **Note:** Inputs with `type="checkbox"` or `type="radio"` should be placed after their corresponding labels, 
> while selects and all other input types should be placed after their corresponding labels.