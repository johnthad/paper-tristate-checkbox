# paper-tristate-checkbox

`paper-tristate-checkbox` is a Polymer web component similar to
[`paper-checkbox`](https://elements.polymer-project.org/elements/paper-checkbox)
except that it supports an indeterminate state.

Example:

![Alt example](https://raw.githubusercontent.com/johnthad/paper-tristate-checkbox/master/paper-tristate-checkbox.png)

[Demo](http://johnthad.github.io/paper-tristate-checkbox/components/paper-tristate-checkbox/)

The web component handles the `aria-checked` attribute in accordance with the W3C's
[WAI-ARIA 1.0 Authoring Practices](https://www.w3.org/TR/wai-aria-practices/#checkbox).

### Styling

The following custom properties and mixins are available for styling:

Custom property | Description | Default
----------------|-------------|----------
`--paper-tristate-checkbox-unchecked-background-color` | Checkbox background color when the input is not checked | `transparent`
`--paper-tristate-checkbox-unchecked-color` | Checkbox border color when the input is not checked | `--primary-text-color`
`--paper-tristate-checkbox-unchecked-ink-color` | Selected/focus ripple color when the input is not checked | `--primary-text-color`
`--paper-tristate-checkbox-checked-color` | Checkbox color when the input is checked | `--primary-color`
`--paper-tristate-checkbox-checked-ink-color` | Selected/focus ripple color when the input is checked | `--primary-color`
`--paper-tristate-checkbox-checkmark-color` | Checkmark color | `white`
`--paper-tristate-checkbox-label-color` | Label color | `--primary-text-color`
`--paper-tristate-checkbox-label-spacing` | Spacing between the label and the checkbox | `8px`
`--paper-tristate-checkbox-error-color` | Checkbox color when invalid | `--error-color`
`--paper-tristate-checkbox-size` | Size of the checkbox | `18px`


#### From `paper-checkbox`__:__

> This element applies the mixin `--paper-font-common-base` but does not import `paper-styles/typography.html`.
> In order to apply the `Roboto` font to this element, make sure you've imported `paper-styles/typography.html`.
