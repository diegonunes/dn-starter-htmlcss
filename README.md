# HTML CSS Default Starter

- Save time on project setup.
- Less lines of CSS.

## Normalize

Small CSS file that provides cross-browser consistency in the default styling of HTML elements.

- Go to [Docs ](https://necolas.github.io/normalize.css/)
- Choose download and copy the latest version
- Create normalize.css
- Setup the link in the html

```html
<link rel="stylesheet" href="./assets/css/normalize.css" />
```

## Colors

```css
:root {
  /* primary */
  /* grey */
  --black: #222;
  --white: #fff;
  --red-light: #f8d7da;
  --red-dark: #842029;
  --green-light: #d1e7dd;
  --green-dark: #0f5132;
}
```

#### Select Primary

Manual Approach

- [coolors](https://coolors.co/)
- [happyhues](https://www.happyhues.co/)
- select your own color
- get shades [shadowlord](https://noeldelgado.github.io/shadowlord/#645cff)

Library/Faster Approach

- [bootstrap](https://getbootstrap.com/docs/5.0/customize/color/#color-sass-maps)
- [tailwind](https://tailwindcss.com/docs/customizing-colors#color-palette-reference)

#### Select Grey

- [tailwind](https://tailwindcss.com/docs/customizing-colors#color-palette-reference)
