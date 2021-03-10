### Color system for dark OR light mode websites

You will need at least 2 colors: one for the background and one for the text.
You can also add 2 extra colors that can be used to slightly differentiate an element's color from the background / text colors.

> Below is an example for light background website:

```css
html {
  --clr-bg: #f0f0f0;
  --clr-bg-dim: #39393d;
  --clr-txt: #1f2020;
  --clr-txt-dim: #aba5b1;

  /* still missing shades of grey and should readjust above colors */
}
```

### Color system for dark AND light mode websites

Similar to above, to make it easy, use the background color as your text color and vice-versa when switching color mode.
The main difference is that if you're using branded colors you may need to adjust each color from your palette for the dark / light mode as they will look very different on light/dark background/text.

---

###### to add...

- Handling dark / light mode switch and storing preference
- Automatic dark / light based on current time of the day
