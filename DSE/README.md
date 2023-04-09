Our globals are split into two parts, one that foundations and one that base.

Foundation consists of system variables, colors, typography, and mixins.

```css
/* system variables */
$dark: #1d1f22;
$dark-light: #737680;

/* colors */
$body-text-color: var(--dse-body-text-color, $dark) !default;
$body-bg-color: var(--dse-body-bg-color, $white) !default;

/* typography */
$body-font-size: var(--dse-body-font-size, $fs-sm) !default;
$body-font-weight: var(--dse-body-font-weight, $fw-normal) !default;
```

