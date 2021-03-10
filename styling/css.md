# Architecture

- font
- color
- space (for things that control the layout spaces)
- default (resets / default HTML element styling)
- utils (utility animations, classes, etc.)

> If using SASS, split the above topics in several partials.

---

# Variable naming convention

Variables should follow the following scheme: `--prefix-name-suffix`.
Both prefix and name are required and the suffix is used to give additional info when more than one variable is needed for the same name (ex: `--clr-orange-dark` and `--clr-orange-light`)

## Common variables

### Fonts

- Default text font `--font`
- Fallback (system fonts) `--font-fallback`
- Header font `--font-h` (if applicable)

### Colors

- Background `--clr-bg`
- Background diminished (closer to the text color) `--clr-bg-dim`
- Text `--clr-txt`
- Text diminished (closer to the background color) `--clr-txt-dim`
- Shades of grey (to create depth) `--clr-grey`, `--clr-grey-txt`, `--clr-grey-bg`, `--clr-grey-transp` (transparent grey)
- Additional palette colors (brand colors for example) `--clr-1`, `--clr-2` (for primary & secondary colors, `--clr-1-x` is typically used for additional colors used to make a gradient)

### Space

- Page-level left and right padding `--space-sides` (usually 20px on mobile and above 80px on desktop)
- Max content width `--space-max-width` (to prevent content from stretching to much on desktop, usually between 600px and 1000px for a 1-column layout)
