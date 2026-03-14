# FFA Course Labs Components

This repository contains standalone HTML components used in Teachable pages for Future Fiction Academy.

Each file is published with GitHub Pages and can be embedded on Teachable using an `iframe`.

## Base Embed Pattern

Use this pattern for any component:

```html
<iframe
  src="https://future-fiction-academy.github.io/ffa-course-labs/<component-file>.html"
  width="100%"
  height="300"
  style="border:0; border-radius:12px; overflow:hidden;"
  loading="lazy"
  title="Component Title">
</iframe>
```

## Example: `email-the-dean.html`

```html
<iframe
  src="https://future-fiction-academy.github.io/ffa-course-labs/email-the-dean.html"
  width="100%"
  height="300"
  style="border:0; border-radius:12px; overflow:hidden;"
  loading="lazy"
  title="Email The Dean">
</iframe>
```

## Available Components

- `email-the-dean.html`  
  `https://future-fiction-academy.github.io/ffa-course-labs/email-the-dean.html`
- `discord-invite.html`  
  `https://future-fiction-academy.github.io/ffa-course-labs/discord-invite.html`
- `tokens.html`  
  `https://future-fiction-academy.github.io/ffa-course-labs/tokens.html`
- `resources.html`  
  `https://future-fiction-academy.github.io/ffa-course-labs/resources.html`

## Notes for Teachable

- Keep `width="100%"` for responsive layouts.
- Adjust `height` per component so content is fully visible.
- `loading="lazy"` helps page performance.
- Keep `style="border:0;"` to remove default iframe borders.

