# FloraVision

FloraVision is a modern, visually rich landing page for an indoor plant store built with React, Vite, and Tailwind CSS. The experience highlights trendy plants, featured products, customer reviews, and clear calls to action.

## Features

- Responsive hero section with a polished plant-focused layout
- Curated plant collections and trend highlights
- Customer review cards and recommendation sections
- Clean, modern UI designed for a premium storefront experience

## Tech Stack

- React 19
- Vite 7
- Tailwind CSS 4
- ESLint

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the development server:
   ```bash
   npm run dev
   ```
3. Open the local preview URL shown in the terminal.

## Build for Production

```bash
npm run build
```

## Live Demo

Add your deployed website URL here:

- Live URL: https://floravision-324u.onrender.com

## Folder and File Structure

```text
FloraVision/
├── public/                          # Static assets
├── src/
│   ├── assets/
│   │   ├── index.js                 # Asset exports
│   │   ├── customers/              # Customer images
│   │   ├── fonts/                  # Font files and CSS
│   │   └── plants/                 # Plant images
│   ├── components/
│   │   ├── header.jsx              # Top navigation bar
│   │   ├── sections/
│   │   │   ├── footer.jsx          # Footer section
│   │   │   ├── heading.jsx         # Reusable section heading
│   │   │   ├── hero.jsx            # Hero section
│   │   │   ├── recommended.jsx     # Recommendations section
│   │   │   ├── trend.jsx           # Trend section
│   │   │   └── review/
│   │   │       ├── card.jsx        # Review card component
│   │   │       ├── index.jsx       # Review section container
│   │   │       └── stars.jsx       # Star rating component
│   │   └── ui/
│   │       ├── button.jsx          # Reusable button
│   │       └── cards/
│   │           ├── card.jsx        # Base card component
│   │           └── clipped.jsx     # Clipped card effect component
│   ├── config/
│   │   ├── navigation.config.js    # Navigation links
│   │   ├── review.config.js        # Review content
│   │   ├── top.config.js           # Top products content
│   │   └── trend.config.js         # Trend product content
│   ├── App.jsx                     # Main app component
│   ├── index.css                   # Global styles
│   └── main.jsx                    # Application entry point
├── index.html                      # Vite HTML template
├── package.json                    # Scripts and dependencies
├── vite.config.js                  # Vite configuration
└── README.md                       # Project documentation
```
