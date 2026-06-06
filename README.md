# Lumina

A luxury travel booking website built with HTML, SCSS, and CSS.

## Demo

Watch the demo video:

<video src="lumina.mp4" controls width="100%"></video>

## Overview

Lumina is a modern, The project uses a modular CSS architecture with BEM-style naming conventions.

## Features

- **Responsive Layout**: Grid-based layout using custom CSS classes for columns (1-of-2, 1-of-3, 1-of-4, 1-of-6)
- **Component-Based Architecture**: Modular SCSS structure with abstracts, base, components, layouts, and pages
- **Custom Icon Font**: Includes `icon-font.css` for icon rendering
- **Modern Design**: Uses Playfair Display and Lato fonts with a clean, luxury aesthetic
- **Interactive Elements**: Hover effects on cards, buttons, and destination images
- **Animations**: CSS keyframe animations for smooth page transitions

## Project Structure

```
lumina/
├── index.html              # Main HTML file
├── css/
│   ├── style.css          # Compiled CSS
│   ├── style.css.map      # Source map
│   └── fonts/             # Icon font files
├── scss/
│   ├── abstracts/         # Variables and mixins
│   │   ├── _index.scss
│   │   ├── _variables.scss
│   │   └── _mixin.scss
│   ├── base/              # Base styles and utilities
│   │   ├── _index.scss
│   │   ├── _base.scss
│   │   ├── _typography.scss
│   │   ├── _utilities.scss
│   │   └── _animations.scss
│   ├── components/        # Reusable components
│   │   ├── _index.scss
│   │   ├── _button.scss
│   │   ├── _destination.scss
│   │   ├── _feature.scss
│   │   ├── _offers.scss
│   │   ├── _social-proof.scss
│   │   └── _value-card.scss
│   ├── layouts/           # Layout styles
│   │   └── _index.scss
│   ├── pages/             # Page-specific styles
│   │   ├── _index.scss
│   │   └── _home.scss
│   └── style.scss         # Main SCSS entry point
├── assets/
│   ├── icon/              # SVG icons
│   └── img/               # Images and photos
└── README.md              # This file
```

## Getting Started

No build process required - the project uses vanilla HTML and CSS. Simply open `index.html` in a browser.

### To Compile SCSS (if making changes)

```bash
# Using Sass CLI
sass scss/style.scss css/style.css

# Or with watch mode
sass --watch scss/style.scss css/style.css
```

## Technology Stack

- **HTML5** - Semantic markup
- **SCSS/Sass** - CSS preprocessing with modular architecture
- **Vanilla CSS** - For the final compiled stylesheet

## Color Palette

- Primary: `#0F172A` (Dark blue)
- Secondary: `#14B8A6` (Teal)
- Tertiary: `#F1F5F9` (Light gray)
- Neutral: `#0B1220` (Black)

## Grid System

- Max width: 180rem
- Vertical gutter: 8rem
- Horizontal gutter: 6rem
- Column classes: `col-1-of-2`, `col-1-of-3`, `col-2-of-3`, `col-1-of-4`, `col-1-of-6`

## Utilities

- `.u-center-text` - Center text alignment
- `.u-margin-bottom-{big,medium,small}` - Bottom margin utilities
- `.u-margin-top-{huge,big,medium,small}` - Top margin utilities

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

MIT License