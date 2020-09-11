# CSS Framework

## Grid System
- A similar to bootstrap grid system, with
  - .container
  - .row
  - .col-(1 to 12)
  
## Margin
- m-(0 to 5 / auto)
- mt-(0 to 5 / auto) (top)
- mb-(0 to 5 / auto) (bottom)
- ml-(0 to 5 / auto) (left)
- mr-(0 to 5 / auto) (right)
- mx-(0 to 5 / auto) (along x-axis)
- my-(0 to 5 / auto) (along y-axis)

## Padding
- Same as margin but "p" instead of "m"

## Colors
- Can be found in scss/utils/_colors.scss
  - Can be used for backgrouns with bg-(color)
  - Can be used for text with txt-(color)
  
## Form
- Only have input field, and label, and text support for now
- .form-group (for grouping labels and inputs)
- .form-input (for an input field)
- .form-text (for a small text beneath the input field)
- Any label inside a form-group is styles automatically
