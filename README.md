**English** | [Русский](README.ru.md)

# Slozhno sosredotochitsya («Hard to Focus»)

A responsive website layout for different screen sizes (mobile, tablet, desktop) with light and dark themes, plus automatic theme switching based on the user's system settings.

---

## Tech Stack

[![Skills](https://skillicons.dev/icons?i=html,css)](https://skillicons.dev)

## Preview

https://github.com/user-attachments/assets/67245611-b6f9-42db-b127-be19bb89f490

Live demo: [click](https://yaylnt.github.io/slozhno-sosredotochitsya-fd/)

To run the project locally, use Live Server.

## My Contribution

- Built a responsive site using the mobile-first approach: media queries for screens wider than 768px and 1024px, fluid layout with no horizontal scrolling.

- Implemented light and dark themes with automatic switching based on system settings via `prefers-color-scheme` and `color-scheme`.

- Added manual theme switching with buttons: `theme-light`, `theme-dark`, and `theme-auto` classes, an active button state, and `pointer-events: none`.

- Moved colors, fonts, sizes, and spacing into CSS variables; themes override them through separate `dark.css` and `light.css` files.

- Built the layout mainly with Grid and Flexbox: header, sections, gallery, footer, with alignment via `justify-self`, `align-self`, and centering.

- Made typography responsive: heading sizes via `clamp()`, `text-shadow`, and decorative backgrounds through a reusable class.

- Created decorative elements (corner marks, the REC label, the dot) with pseudo-elements and absolute positioning.

- Worked out interactive states: `:hover`, `:focus-visible`, borders, underlines, shadows, and accessible focus styles.

- Used semantic markup: `section`, `article`, a single `h1`, `alt` text for images, and `loading="lazy"` for the gallery.

- Considered accessibility: decorative text is hidden from screen readers with `aria-hidden`, with careful focus handling and keyboard navigation.

- Organized the CSS structure: `variables.css`, `style.css`, `dark.css`, `light.css`, keeping the cascade and import order consistent.

- Verified correct rendering in 6 combinations: light / dark / auto theme under both light and dark system modes.