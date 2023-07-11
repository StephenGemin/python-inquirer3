---
myst:
  substitutions:
    inquirer checkbox: |-
      ```{image} images/inquirer_checkbox.gif
      :alt: Example of Checkbox Question
      ```
    inquirer confirm: |-
      ```{image} images/inquirer_confirm.png
      :alt: Example of Confirm Question
      ```
    inquirer list: |-
      ```{image} images/inquirer_list.png
      :alt: Example of List Question
      ```
    inquirer text: |-
      ```{image} images/inquirer_text.png
      :alt: Example of Text Question
      ```
    inquirer theme: |-
      ```{image} images/inquirer_theme.gif
      :alt: Example of theme (GreenPassion)
      ```
---

# Examples

You can find all these examples at {code}`examples` directory.

## text.py

```{literalinclude} ../examples/text.py

```

Result on something like:

{{ inquirer text }}

## confirm.py

```{literalinclude} ../examples/confirm.py

```

Result on something like:

{{ inquirer confirm }}

## list.py

```{literalinclude} ../examples/list.py

```

Result on something like:

{{ inquirer list }}

## checkbox.py

```{literalinclude} ../examples/checkbox.py

```

Result on something like:

{{ inquirer checkbox }}

Apart from all the controlls supported by other questions, checkbox supports some more as shown above:

- `Ctrl + A` to select all.
- `Ctrl + R` to un-select all the choices, even the defaults.
- `Ctrl + I` to invert/toggle all the choices.

The {code}`choices` list can also be a list of tuples. The first value in each tuple should be the label displayed to the user. The second value in each tuple should be the actual value for that option. This allows you to have the user choose options that are not plain strings in the code.

```{literalinclude} ../examples/checkbox_tagged.py

```

## theme.py

```{literalinclude} ../examples/theme.py

```

Result on something like:

{{ inquirer theme }}
