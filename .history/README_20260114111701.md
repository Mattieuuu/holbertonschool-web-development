# Holbertonschool Web Development

This repository contains web development projects focusing on HTML, CSS, and responsive design principles.

## Requirements

- **Allowed editors**: vi, vim, emacs
- **HTML and CSS rendered on**: Chrome 78 or more
- **README.md**: Mandatory at the root of the project directory

## Project Structure

### css_advanced/
Advanced CSS techniques and styling
- `index.html` - Main HTML file
- `styles.css` - Advanced CSS stylesheet
- `images/` - Image assets

### html_advanced/
Advanced HTML structure and semantic markup
- `index.html` - Main HTML file
- `README.md` - Project-specific documentation

### responsive_design/
Responsive design implementation with breakpoints
- `00-index.html` / `00-styles.css` - Initial responsive design
- `01-index.html` / `01-styles.css` - Enhanced responsive design
- `02-index.html` / `02-styles.css` - Improved responsive design
- `03-index.html` / `03-styles.css` - Advanced responsive design with responsive images
- `images/` - Image assets including responsive breakpoints

### images/
Shared image resources across projects

## Responsive Design Implementation

### 03-index.html - Responsive Images with Picture Element

The `03-index.html` file demonstrates best practices for responsive images using the HTML5 `<picture>` element with multiple breakpoints:

#### Breakpoint Configuration
- **Mobile**: 380px
- **Tablet**: 853px
- **Desktop**: 1200px

#### Responsive Images Implemented
1. **pic-about-01.jpg** - About Us section
   - pic-about-01_w_380.jpg (mobile)
   - pic-about-01_w_853.jpg (tablet)
   - pic-about-01_w_1200.jpg (desktop)

2. **pic-article-01.jpg** - Article 1
   - pic-article-01_w_380.jpg (mobile)
   - pic-article-01_w_853.jpg (tablet)
   - pic-article-01_w_1200.jpg (desktop)

3. **pic-article-02.jpg** - Article 2
   - pic-article-02_w_380.jpg (mobile)
   - pic-article-02_w_853.jpg (tablet)
   - pic-article-02_w_1200.jpg (desktop)

4. **pic-article-03.jpg** - Article 3
   - pic-article-03_w_380.jpg (mobile)
   - pic-article-03_w_853.jpg (tablet)
   - pic-article-03_w_1200.jpg (desktop)

#### Markup Example
```html
<picture>
  <source media="(min-width: 1200px)" srcset="images/pic-about-01_w_1200.jpg 1200w">
  <source media="(min-width: 853px)" srcset="images/pic-about-01_w_853.jpg 853w">
  <source media="(min-width: 380px)" srcset="images/pic-about-01_w_380.jpg 380w">
  <img src="images/pic-about-01_w_380.jpg" alt="About us image" width="460" height="460">
</picture>
```

## Key Features

### Responsive Design
- Fluid layouts that adapt to different screen sizes
- Media queries for device-specific styling
- Flexible grid systems
- Responsive images with multiple breakpoints

### HTML5 Semantics
- Proper semantic HTML structure
- Accessible markup
- SEO-friendly content organization

### CSS Best Practices
- CSS variables for maintainability
- Normalized styling across browsers
- Optimized selectors and organization
- Responsive typography

## Browser Compatibility

All HTML and CSS has been tested and rendered on Chrome 78 or higher.

### Supported Features
- CSS Grid
- Flexbox
- CSS Variables
- Media Queries
- Picture Element
- Responsive Images with srcset

## Usage

1. Open any HTML file in Chrome 78 or higher
2. The responsive design will automatically adapt to your screen size
3. Test different viewport sizes using browser DevTools

### Testing Responsive Design
- Mobile (380px and below)
- Tablet (853px)
- Desktop (1200px and above)

## File Structure
```
holbertonschool-web-development/
├── README.md
├── css_advanced/
│   ├── index.html
│   ├── styles.css
│   └── images/
├── html_advanced/
│   ├── index.html
│   └── README.md
├── responsive_design/
│   ├── 00-index.html
│   ├── 00-styles.css
│   ├── 01-index.html
│   ├── 01-styles.css
│   ├── 02-index.html
│   ├── 02-styles.css
│   ├── 03-index.html
│   ├── 03-styles.css
│   ├── README.md
│   └── images/
│       ├── banner-home.jpg
│       ├── favicon.jpg
│       ├── logo-black.png
│       ├── logo-white.png
│       ├── pic-about-01_w_*.jpg
│       ├── pic-article-01_w_*.jpg
│       ├── pic-article-02_w_*.jpg
│       ├── pic-article-03_w_*.jpg
│       └── [other assets]
└── images/
```

## Development

When editing these files, use one of the allowed editors:
- **vi** - Classic vi editor
- **vim** - Improved vi editor
- **emacs** - GNU Emacs editor

Example:
```bash
vim responsive_design/03-index.html
```

## Author

Mattieuuu

## License

This project is part of the Holbertonschool curriculum.
