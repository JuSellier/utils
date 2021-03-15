# utils

Useful web development stuff for me to remember.

- Typography
- Colors
- UI elements (buttons, links, modals, header, footer, etc.)
- Useful tools

---

---

# Overview

## Frontend

### Styling

#### Typography

- Font families
- Sizes (headings, text, small text, etc.)
- Weights

> Note for weights: In the near future, we should be able to use more and more variable fonts on websites. This would facilitate font weight management.

#### Colors

Required:

- Black / White / Shades of grey

Optional:

- Palette (branded colors)
- Success (green) / Warning (yellow) / Error (red)
- Dark & Light Mode

#### Common elements (default styling)

| Name        | HTML tag(s)                      |
| ----------- | -------------------------------- |
| Header      | `header`                         |
| Footer      | `footer`                         |
| Headings    | `h1`, `h2` to `h6`               |
| Buttons     | `button`                         |
| Links       | `a`                              |
| Paragraphs  | `p`                              |
| Form inputs | `input[type="text"]`, `textarea` |

### Internationalisation & Localisation

#### Multi-language support

Many libraries are available for adding multiple languages to websites.

> Important: If you care about SEO, it may be a bit more tricky to add multi-language support as you need seperate pages for each language. See "indexing" below for more info about how indexing multiple languages work.

#### Indexing: Using Paths vs Domains vs Subdomains

Depending on the framework & i18n library you use, you may be able to use domains or subdomains to differentiate between languages.

##### Path routing (most common)

It is common to setup up languages on a website so that all pages from a languages will exist under a path corresponding the language.
For example: the contact page `website.com/contact` would become `website.com/fr/contact` for the French version and `website.com/es/contact` for Spanish.

##### Domain

Another common way to do that is to use a different domain for each language.
For example: the contact page `website.com/contact` becomes `website.fr/contact`.

> Note: You will need to purchase another domain if you choose this option.

##### Subdomains

It consists in using a subdomain to differentiate languages.
For example: the French version of contact page (used in the above examples) would be hosted under `fr.website.com/contact`, `es.website.com/contact`

> Note: Don't use this option if you plan on using subdomains for other stuff.

### State Management

Global state keeps independent components up to date with global application data.

#### React

Context API / Hooks allow you to implement global state without using redux.

#### Svelte

Built-in stores.

### Web Accessibility

This is about making web pages more accessible to people with disabilities.
Web Accessibility aims at providing solutions for people that are(partly or totally):

#### Blind

Solutions:

- Use screenreader-friendly markup (ARIA) in your HTML.
- Make sure navigation/interactions with keyboard is possible.

#### Deaf

Solutions:

- Provide text transcriptions for videos and audio files.
- You can also provide visual cues that a sound is playing when possible.

#### Paralized

Solutions:

- Make sure you can navigate through the page and interact with buttons/links/inputs/etc. with the keyboard only.
- Offer speech to text inputs when possible

---

## Backend

### Database

#### Database types

Most common:

- NoSQL
- SQL

If you're not sure which database type you should be using. Go for NoSQL (it's easier to implement and less strict).

#### Database design

Very important process that has a lot to do with information architecture.

### Notifications

#### Email sending

For NodeJS, use nodemailer is pretty good.

#### SMS sending

Not done yet.

---

## General & DevOps

### Website deployment

Depends if your website is:

- Static
- Client-side rendered
- Server-side rendered

Common solutions:

- Netlify
- Vercel

### Server deployment

NodeJS: Heroku

### Analytics

For websites & mobile apps: Google Analytics / Google Tags Manager
For servers: ???
