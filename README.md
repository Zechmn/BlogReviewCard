# Blog Review Card

## Overview

This project is a responsive blog review card component built using pure vanilla HTML and CSS. It's a static implementation showcasing a modern card design with hover states, focus accessibility, and clean typography. The component displays blog post review information including an illustration, category tag, publication date, title, description, and author details. The implementation follows accessibility best practices with proper keyboard navigation and semantic markup.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Static Site Structure**: Pure HTML5 with semantic markup using `<main>`, `<article>`, and proper heading hierarchy
- **CSS Architecture**: Modern CSS with custom properties (CSS variables) for consistent theming and color management
- **Typography System**: Custom font loading using `@font-face` with Figtree font family, implementing font-display: swap for performance
- **Responsive Design**: Flexbox-based layout with mobile-first approach, designed for 375px mobile and 1440px desktop breakpoints
- **Component-Based Styling**: Modular CSS classes following BEM-like naming conventions (card-*, author-*, etc.)

### Design System
- **Color Palette**: Centralized color system using CSS custom properties with semantic naming
- **Typography Scale**: Consistent font weights (500 Medium, 800 ExtraBold) with 16px base font size
- **Layout Strategy**: Centered card layout using flexbox with proper spacing and responsive padding

### Performance Considerations
- **Font Optimization**: Local font files with font-display: swap for improved loading performance
- **Image Assets**: Optimized images with proper alt attributes for accessibility
- **Minimal Dependencies**: No external frameworks or libraries, pure HTML/CSS implementation

## External Dependencies

### Fonts
- **Figtree Font Family**: Custom font loaded locally via TTF files
  - Medium (500 weight)
  - ExtraBold (800 weight)
  - Licensed under SIL Open Font License

### Assets
- **Static Images**: 
  - Favicon (32x32 PNG)
  - Blog illustration (PNG)
  - Author avatar (WebP format)
- **No External APIs**: Fully self-contained static implementation
- **No Build Tools**: Direct HTML/CSS without compilation or bundling requirements

### Development Context
- **Frontend Mentor Challenge**: Built as a coding challenge for skill development
- **Browser Compatibility**: Modern CSS features requiring recent browser support for custom properties and flexbox
