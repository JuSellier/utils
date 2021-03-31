# System fonts

```css
font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen-Sans,
  Ubuntu, Cantarell, "Helvetica Neue", Helvetica, Arial, sans-serif;
```

---

# Best Google Fonts

## Sans-serif

| Font Name     | Notes                            |
| ------------- | -------------------------------- |
| Poppins       | Clean & Modern.                  |
| IBM Plex Sans | Professional                     |
| Roboto        | Safe pick.                       |
| Montserrat    | Good for headers, safe pick.     |
| Alegreya Sans | Good for long text, bit stylish. |

## Monospace

| Font Name     | Notes          |
| ------------- | -------------- |
| Roboto Mono   | Safe pick.     |
| Syne Mono     | Stylish, dark. |
| Inconsolata   | Clean, slick.  |
| Courier Prime | Journalistic.  |

## Serif

| Font Name        | Notes        |
| ---------------- | ------------ |
| BioRhyme         | Modern, slab |
| Source Serif Pro | Historical   |
| Josefin Slab     | 1930's style |
| Roboto Slab      | Robust       |

## Stylish

| Font Name     | Notes                       |
| ------------- | --------------------------- |
| Orbitron      | Cyberpunk, Futuristic       |
| Space Grotesk | Futuristic yet professional |

## Handwriting

| Font Name      | Notes                  |
| -------------- | ---------------------- |
| Gaegu          | Childish               |
| Amatic SC      | All caps, teenager-ish |
| Dancing Script | Fancy                  |

---

# Sizes

Horizontal space is the main concern when textual sizing elements as the text will easily overflow on mobile devices if it is too big. To solve this problem, you can use the window width in your font-size calculation.

### Don't want to use calculations?

```css
--size-h1: 2.2rem;
--size-h2: 2rem;
--size-h3: 1.7rem;
--size-h4: 1.6rem;
--size-h5: 1.3rem;
--size-h6: 1.1rem;
```

---

# Font weights

> Note: When using dark/light mode, text will appear thinner in light mode. (maybe think of a way to adjust font weight)

Example with Montserrat: weight 400 on light background looks around the same boldness as weight 100 on dark background
