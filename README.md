# Bike Landing Page — Take the Streets

This project is a responsive landing page for a bike brand. It presents the product line, a comparison of bike models, detailed feature descriptions and a contact form, with a mobile burger menu and smooth hover effects.

## Live Demo

Experience the live website: [Bike Landing Page Demo](https://zakys1d.github.io/my-bike-landing-page/)

## Design Reference

The layout is based on the Figma design: [Figma mockup](https://www.figma.com/) <!-- TODO: replace with the direct link to your Figma file -->

## Technologies Used 💻

### Core

- **HTML5** – Semantic markup
- **SCSS** – Styling, BEM methodology, mixins and variables

### Development & Deployment

- **Parcel** (v2.12) – Build tool and dev server
- **Stylelint** (v16.7) – SCSS code quality
- **ESLint** (v8.57) / **Prettier** (v3.3) – JavaScript code quality and formatting
- **@mate-academy/scripts** – Project scripts (start, build, lint, deploy)
- **GitHub Pages** – Hosting and deployment

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/Zakys1d/my-bike-landing-page.git
cd my-bike-landing-page
```

2. Install dependencies:

```bash
npm install
# or
yarn install
```

3. Run the project locally:

```bash
npm start
# or
yarn start
```

Other useful commands:

```bash
npm run lint    # check code style
npm run build   # production build
npm run deploy  # deploy to GitHub Pages
```

## Features

- **Responsive Design**: Optimized for mobile, tablet and desktop screens.
- **Burger Menu**: Full-screen mobile navigation opened and closed with the `#menu` anchor.
- **Smooth Navigation**: Menu links scroll to the About, Compare Bikes, Details and Contacts sections.
- **Product Cards**: Bike cards with hover animation (lift and shadow).
- **Compare Bikes**: Section for comparing bike models side by side.
- **Details Section**: Feature blocks with image hover effects.
- **Contact Form**: Form for sending a request to the bike shop.
- **Click-to-Call**: Phone numbers use `tel:` links for quick calling on mobile devices.
