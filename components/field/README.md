# Field

### Blocks

| Block          | Description                                                                                       |
| -------------- | ------------------------------------------------------------------------------------------------- |
| field          | Creates a field for use with forms, containing a label, input, and optional error.                |

### Nodes

| Node         | Description                                                                             |
| ------------ | --------------------------------------------------------------------------------------- |
| label        | Defines the field label.                                                                |
| input/select | Defines the field input. This can be an input element of any type, or a select element. |
| ul/ol        | Defines the field errors list. Each error should live in it's own `li`.                 |
| ul/ol > li   | Defines the field error itself.                                                         |

> **Note:** Inputs with `type="checkbox"` or `type="radio"` should be placed before their corresponding labels, 
> with their field error `ul` or `ol` immediately after their corresponding labels; 
> while selects and all other input types should be placed after their corresponding labels, followed immediately
> by their field error `ul` or `ol`.