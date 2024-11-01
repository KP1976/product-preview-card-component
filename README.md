# Product Card Component

This is a solution to the Product Card Component challenge, showcasing a responsive product card design for a perfume product.

## Table of Contents

- [Overview](#overview)
  - [Features](#features)
  - [Screenshots](#screenshots)
- [Project Structure](#project-structure)
- [Implementation Details](#implementation-details)
  - [Built with](#built-with)
  - [CSS Architecture](#css-architecture)
  - [Responsive Design](#responsive-design)
- [Getting Started](#getting-started)
- [Author](#author)

## Overview

### Features

- Responsive layout that adapts to different screen sizes
- Modern CSS architecture using SCSS
- Optimized images with WebP format and proper srcset implementation
- Custom font loading with performance optimization
- Interactive states for buttons and links

### Screenshots

#### Desktop View

![Desktop Design](design/desktop-preview.jpg)

#### Mobile View

![Mobile Design](design/mobile-design.jpg)

## Project Structure

```
├── assets/
│   ├── fonts/
│   │   ├── fraunces-v31-latin-700.woff2
│   │   ├── montserrat-v26-latin-500.woff2
│   │   └── montserrat-v26-latin-700.woff2
│   └── images/
│       ├── image-product-desktop.jpg
│       ├── image-product-desktop.webp
│       ├── image-product-mobile.jpg
│       └── image-product-mobile.webp
├── scss/
│   ├── abstracts/
│   │   ├── _mixins.scss
│   │   └── _variables.scss
│   ├── base/
│   │   ├── _fonts.scss
│   │   └── _reset.scss
│   ├── components/
│   │   └── _card.scss
│   └── layout/
│       ├── _footer.scss
│       └── _main.scss
├── index.html
└── main.css
```

## Implementation Details

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- SCSS
- Modern CSS reset
- Optimized font loading

### CSS Architecture

The project uses a modular SCSS architecture with:

- Modern CSS reset for consistent cross-browser styling
- Custom font declarations with optimized loading strategies
- Component-based styling with BEM methodology
- Responsive design using media queries
- CSS custom properties for theme colors and reusable values

### Responsive Design

- Mobile-first approach with breakpoint at 600px
- Flexible images with srcset for different viewport sizes
- Responsive typography and spacing
- Optimized layouts for both mobile and desktop views

## Getting Started

1. Clone the repository
2. Ensure you have a SCSS compiler installed
3. Run the SCSS compiler to watch for changes:
   ```bash
   sass --watch scss:css
   ```
4. Open `index.html` in your browser

## Author

- Frontend Mentor - [@kp1976](https://www.frontendmentor.io/profile/KP1976)
- Coded by Krzysztof Pawłowski
