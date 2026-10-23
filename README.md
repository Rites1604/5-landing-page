# Studio Five — Five Business Landing Pages

A responsive React + Vite showcase containing five distinct, interactive landing page concepts.

## Included designs

1. **Haven & Hill** — real estate listings and site-visit inquiry
2. **Goodside Studio** — creative / digital marketing agency
3. **Craft Academy** — course discovery and enrollment inquiry
4. **Kindred Dental** — dental clinic treatments and appointment inquiry
5. **Ever After Studio** — wedding photography gallery and availability inquiry

## Features

- Switch between all five designs from the sticky showcase navigation.
- Five separate visual identities, layouts, color systems, and typography treatments.
- Responsive mobile navigation and mobile-first breakpoints.
- Interactive inquiry modal with validation and success state.
- Property cards, service lists, course cards, treatment cards, and photography gallery.
- Keyboard-friendly buttons, accessible form labels, and reduced-motion support.

## Run locally

Requires Node.js 18 or newer.

```bash
npm install
npm run dev
```

Open the local URL printed by Vite.

## Production build

```bash
npm run build
npm run preview
```

## Important notes

- Inquiry forms are frontend demos. They do not send or store submissions. Connect them to a backend, email service, or CRM before using them for a real business.
- Photography is loaded from Unsplash URLs and Google Fonts are loaded externally, so an internet connection is required for those assets.
- Replace demo statistics, testimonials, business copy, and imagery with verified client information before publishing commercially.

## Publish on GitHub

Create a repository named `five-business-landing-pages`, then from this project directory run:

```bash
git init
git add .
git commit -m "Build five interactive business landing pages"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/five-business-landing-pages.git
git push -u origin main
```

To publish with GitHub Pages, configure the repository's Pages settings or add an appropriate deployment workflow for Vite.
