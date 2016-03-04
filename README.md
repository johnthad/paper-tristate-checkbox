# tristate-checkbox

`tristate-checkbox` is a Polymer web component similar to 
[`paper-checkbox`](https://elements.polymer-project.org/elements/paper-checkbox) 
except that it supports an indeterminate state.

Example:

![Alt example](../blob/master/tristate-checkbox.png)

The web component handles the `aria-checked` attribute in accordance with the W3C's
[WAI-ARIA 1.0 Authoring Practices](https://www.w3.org/TR/wai-aria-practices/#checkbox).

### Styling

The following custom properties and mixins are available for styling:

Custom property | Description | Default
----------------|-------------|----------
`--tristate-checkbox-unchecked-background-color` | Checkbox background color when the input is not checked | `transparent`
`--tristate-checkbox-unchecked-color` | Checkbox border color when the input is not checked | `--primary-text-color`
`--tristate-checkbox-unchecked-ink-color` | Selected/focus ripple color when the input is not checked | `--primary-text-color`
`--tristate-checkbox-checked-color` | Checkbox color when the input is checked | `--primary-color`
`--tristate-checkbox-checked-ink-color` | Selected/focus ripple color when the input is checked | `--primary-color`
`--tristate-checkbox-checkmark-color` | Checkmark color | `white`
`--tristate-checkbox-label-color` | Label color | `--primary-text-color`
`--tristate-checkbox-label-spacing` | Spacing between the label and the checkbox | `8px`
`--tristate-checkbox-error-color` | Checkbox color when invalid | `--error-color`
`--tristate-checkbox-size` | Size of the checkbox | `18px`


#### From `paper-checkbox`__:__

> This element applies the mixin `--paper-font-common-base` but does not import `paper-styles/typography.html`.
> In order to apply the `Roboto` font to this element, make sure you've imported `paper-styles/typography.html`.
