---
description: Functional CSS for the future
---

# Introducing Pollen

Pollen is a library of [CSS variables](https://developer.mozilla.org/en-US/docs/Web/CSS/--*) for rapid prototyping, consistent styling, and as a zero-runtime [utility-first](https://frontstuff.io/in-defense-of-utility-first-css) foundation for your own design systems. Heavily inspired by [TailwindCSS](https://tailwindcss.com).

### What it looks like

Pollen has no runtime, buildstep, class naming conventions, or framework dependencies. It works in stylesheets, inline styles, and CSS-in-JS.

```css
.button {
  font: var(--font-sans);
  font-weight: var(--font-medium);
  padding: var(--size-1);
  background: var(--color-blue);
  color: white;
  border-radius: var(--radius-2);
  box-shadow: var(--elevation-1);
  transition: background 150ms var(--easing-standard);
}
```

### Modules

* [Typography system](modules/typography.md)
* [Color palette](modules/colors.md)
* [Layout scales](modules/layout.md)
* [UI library](modules/layout.md)

