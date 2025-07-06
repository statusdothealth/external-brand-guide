# Visual Assets Guide

This guide provides detailed specifications for all status.health® visual assets.

## Logo Specifications

### Primary Logo Components

#### The "00" Mark
- **Font**: Georgia (serif)
- **Size**: 22px within 40px container
- **Positioning**: Centered within container
- **Color**: 
  - Light mode: #000000 on #FFFFFF background
  - Dark mode: #FFFFFF on #000000 background

#### The Wordmark
- **Font**: Verdana (sans-serif)  
- **Size**: 24px
- **Weight**: Normal (400)
- **Spacing**: 0.5em between mark and wordmark

### Logo Construction

```
[00] status.health
 ^       ^
 |       |
Mark  Wordmark
```

### Clear Space Requirements

Minimum clear space = ½ height of logo
```
┌─────────────────────────┐
│                         │
│     [00] status.health  │  <- ½ logo height
│                         │
└─────────────────────────┘
```

## Logo Variations

### Available Logo Files

#### Primary Logos
- **logo-dark.svg** - Black logo for light backgrounds
- **logo-light.svg** - White logo for dark backgrounds
- **logo-round.svg** - Circular version of the logo

#### Additional Logos
- **logo-large.svg** - Large format logo for hero sections
- **logo-large-inverted.svg** - Large format with inverted colors
- **logo-inverted.svg** - Standard size with inverted colors
- **icon-light.svg** - Icon-only version for light backgrounds
- **icon-dark.svg** - Icon-only version for dark backgrounds

#### Favicons and App Icons
- **favicon.ico** - Multi-resolution favicon (16x16, 32x32, 48x48)
- **favicon-16x16.png** - 16px favicon
- **favicon-32x32.png** - 32px favicon
- **apple-touch-icon.png** - 180x180px iOS app icon
- **android-chrome-192x192.png** - 192px Android app icon
- **android-chrome-512x512.png** - 512px Android app icon

### Logo Usage Guidelines

#### When to Use Each Logo
- **logo-dark.svg**: Default logo for light backgrounds
- **logo-light.svg**: Use on dark backgrounds or in dark mode
- **logo-round.svg**: Profile images, social media avatars
- **logo-large.svg**: Hero sections, landing pages (min 200px width)
- **icon-*.svg**: When space is limited (under 100px width)

## Color Specifications

### Primary Palette

| Color | Hex | RGB | Usage |
|-------|-----|-----|-------|
| Black | #000000 | 0, 0, 0 | Primary text, dark backgrounds |
| White | #FFFFFF | 255, 255, 255 | Primary backgrounds, dark mode text |

### Secondary Palette

| Color | Hex | RGB | Usage |
|-------|-----|-----|-------|
| Link Blue | #0000EE | 0, 0, 238 | Interactive elements |
| Visited Purple | #551A8B | 85, 26, 139 | Visited links |
| Muted Gray | #666666 | 102, 102, 102 | Secondary text |
| Border Gray | #CCCCCC | 204, 204, 204 | Dividers, borders |

### Dark Mode Colors

| Element | Light Mode | Dark Mode |
|---------|------------|-----------|
| Background | #FFFFFF | #000000 |
| Text | #000000 | #CCCCCC |
| Links | #0000EE | #809FFF |
| Borders | #CCCCCC | #333333 |
| Muted | #666666 | #999999 |

## Typography Specifications

### Font Stack

```css
/* Headings */
font-family: Verdana, Geneva, sans-serif;

/* Body Text */
font-family: Georgia, 'Times New Roman', serif;

/* Code/Technical */
font-family: 'SF Mono', Monaco, 'Inconsolata', 'Fira Code', monospace;
```

### Type Scale

| Element | Size | Line Height | Weight |
|---------|------|-------------|---------|
| H1 | 24px | 1.2 | Bold (700) |
| H2 | 20px | 1.3 | Bold (700) |
| H3 | 18px | 1.4 | Bold (700) |
| Body | 15px | 1.6 | Normal (400) |
| Small | 14px | 1.5 | Normal (400) |
| Code | 14px | 1.4 | Normal (400) |

## Icon Guidelines

### Icon Style
- **Style**: Outline (not filled)
- **Stroke Width**: 1.5px
- **Corner Radius**: 2px for squares
- **Minimum Size**: 16px × 16px

### Common Icons

#### Theme Toggle
- Light mode: "D" (for Dark)
- Dark mode: "L" (for Light)
- Font: Georgia, 12px
- Container: 1px border

#### Navigation
- No custom icons - use text links
- Dropdown arrows: Simple "▼" character

## Button Styles

### Primary Button
```css
background: var(--text-color);
color: var(--bg-color);
border: none;
padding: 10px 20px;
font-family: Georgia, serif;
font-size: 16px;
cursor: pointer;
```

### Secondary Button
```css
background: transparent;
color: var(--text-color);
border: 1px solid var(--text-color);
padding: 10px 20px;
font-family: Georgia, serif;
font-size: 16px;
cursor: pointer;
```

## Layout Guidelines

### Container Widths
- **Maximum**: 600px
- **Padding**: 20px (15px on mobile)
- **Margin**: 0 auto (centered)

### Spacing System
- **Base Unit**: 10px
- **Spacing Scale**: 10px, 20px, 30px, 40px, 60px
- **Inline Spacing**: 5px, 10px, 15px

### Responsive Breakpoints
- **Mobile**: < 600px
- **Desktop**: ≥ 600px

## Accessibility Requirements

### Color Contrast
- **Normal Text**: 4.5:1 minimum
- **Large Text**: 3:1 minimum
- **Interactive Elements**: 3:1 minimum

### Focus States
```css
outline: 2px solid var(--link-color);
outline-offset: 2px;
```

### Motion
- Respect `prefers-reduced-motion`
- Keep transitions under 300ms
- No auto-playing animations

## File Formats

### Logo Files
- **Digital**: SVG (preferred), PNG (fallback)
- **Print**: SVG, PDF, or EPS
- **Sizes**: Provide at minimum 1x, 2x, 4x

### Image Optimization
- **Format**: WebP with JPEG fallback
- **Quality**: 85% for photos, 100% for graphics
- **Loading**: Lazy load below the fold

## Implementation Examples

### HTML Logo Implementation

#### Standard Logo
```html
<!-- Light Mode -->
<img src="/assets/logo-dark.svg" 
     alt="status.health - Zero data. Zero risk." 
     width="160" 
     height="40"
     class="logo-light">

<!-- Dark Mode -->
<img src="/assets/logo-light.svg" 
     alt="status.health - Zero data. Zero risk." 
     width="160" 
     height="40"
     class="logo-dark">
```

#### Large Logo (Hero Sections)
```html
<img src="/assets/additional logos/logo-large.svg" 
     alt="status.health - Zero data. Zero risk." 
     width="320" 
     height="80"
     class="logo-hero">
```

#### Icon Only
```html
<!-- Light Mode -->
<img src="/assets/additional logos/icon-dark.svg" 
     alt="status.health" 
     width="40" 
     height="40"
     class="icon-light">

<!-- Dark Mode -->
<img src="/assets/additional logos/icon-light.svg" 
     alt="status.health" 
     width="40" 
     height="40"
     class="icon-dark">
```

#### Favicon Implementation
```html
<link rel="icon" type="image/x-icon" href="/assets/additional logos/favicon.ico">
<link rel="icon" type="image/png" sizes="32x32" href="/assets/additional logos/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="/assets/additional logos/favicon-16x16.png">
<link rel="apple-touch-icon" sizes="180x180" href="/assets/additional logos/apple-touch-icon.png">
<link rel="icon" type="image/png" sizes="192x192" href="/assets/additional logos/android-chrome-192x192.png">
<link rel="icon" type="image/png" sizes="512x512" href="/assets/additional logos/android-chrome-512x512.png">
```

### CSS Theme Implementation
```css
/* Automatic theme detection */
@media (prefers-color-scheme: dark) {
  :root {
    --bg-color: #000;
    --text-color: #ccc;
    --link-color: #809fff;
  }
}

/* Manual theme toggle */
body.dark-mode {
  --bg-color: #000;
  --text-color: #ccc;
  --link-color: #809fff;
}
```

---

© 2025 Health Protocol Labs, SPC. All rights reserved.