# Digital Marketing & Content Creator Portfolio

A responsive, single-page portfolio template for a digital marketer and content creator. It includes English and Khmer copy, light and dark themes, and lightweight scroll-reveal animations.

## Project files

- `index.html` — page structure, navigation, portfolio sections, and contact links.
- `style.css` — layout, responsive styles, colors, theme variables, and animation styles.
- `script.js` — English/Khmer translations, theme and language controls, calendar-grid decoration, and scroll-reveal behavior.

## Run locally

This is a static site and does not require a build step or package installation. Open `index.html` in a browser, or serve the project folder with any static web server.

The page loads the Kantumruy Pro font from Google Fonts when an internet connection is available; system fonts are used as a fallback.

## Features

- Responsive layout for desktop and mobile screens.
- Navigation links to About, Skills, Services, Work, Experience, and Contact sections.
- English and Khmer language toggle. The selected language is saved in browser storage when available.
- Light and dark theme toggle, with the system color preference used until a theme is selected. The selection is saved in browser storage when available.
- Scroll-reveal effects for page sections and content cards, powered by `IntersectionObserver`.
- Reduced-motion support: reveal transitions and smooth scrolling are disabled when the visitor prefers reduced motion. If `IntersectionObserver` is unavailable, the page content remains visible.

## Personalize the portfolio

1. In `index.html`, replace the sample name, email address, social profile URLs, location, dates, and other placeholder details.
2. Update the displayed portfolio content in `script.js`. The `D.en` and `D.km` objects contain the English and Khmer text keyed by the `data-i` attributes in the HTML.
3. Keep translation keys in `index.html` and both translation objects in sync when adding or renaming translated content.
4. Adjust skills, percentages, statistics, cards, and experience entries in `index.html`.
5. Customize colors, spacing, responsive behavior, and animation timing in `style.css`.

The sample contact details, work examples, metrics, and career history are placeholders; replace them with accurate information before publishing.