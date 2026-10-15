# Zijun Wang — Personal Website

Personal homepage focused on AI and technology business strategy, industry research, product thinking, and cross-functional execution. Current role interests include CEO Office, Strategy & Operations, and New Business, with a longer-term interest in general management and entrepreneurship.

Live site: [zijunvv.github.io](https://zijunvv.github.io/)

## Structure

- `index.html` — standalone homepage, embedded styles, language switching, and navigation.
- `assets/` — portfolio images and the site icon.
- `inner-order-os-architecture.html` — supporting technical project page.
- `.github/workflows/static.yml` — GitHub Pages deployment on pushes to `main`.
- `components/ui/` and `public/` — retained UI components and assets; no build step is required for the homepage.

## Editing and preview

English copy is authored directly in `index.html`. Simplified and Traditional Chinese translations live in the `I18N` dictionaries in the same file. Update all three versions when changing text marked with `data-i18n`; the English markup also serves as the fallback when JavaScript is unavailable.

To preview from the repository directory:

```sh
python3 -m http.server 8000
```

Open `http://localhost:8000` and check language switching, navigation, and the expandable supporting-work section on desktop and mobile widths. No package installation or compilation is needed.

## Content principles

Lead with business questions, evidence, choices, and execution. Use AI, data, and implementation details to support that story. Keep employment titles, organizations, dates, and substantiated results accurate; distinguish independent research and early product experiments from commercial outcomes. Describe target roles and future leadership interests as aspirations.
