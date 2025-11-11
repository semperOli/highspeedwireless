# HighSpeed WISP Website

A modern, responsive website for a Wireless Internet Service Provider (WISP) featuring glassmorphism design elements and smooth user interactions.

## 📁 Project Structure

```
HighSpeed Wireless Website/
├── index.html          # Main HTML file with semantic markup
├── styles.css          # External stylesheet with organized CSS
├── script.js           # External JavaScript for interactions
└── README.md           # Project documentation
```

## ✨ Features

### Design
- **Glassmorphism UI**: Modern frosted glass effect on hero section
- **Responsive Layout**: Mobile-first design that works on all devices
- **Smooth Animations**: Scroll animations and hover effects
- **Clean Typography**: Easy-to-read font hierarchy

### Sections
1. **Hero Section**: Eye-catching introduction with CTA button
2. **Solutions**: Three service offerings (Wireless Broadband, Business, Community)
3. **Packages**: Three pricing tiers (Basic, Standard, Premium)
4. **Contact**: Contact information and form
5. **Footer**: Site links and social media

### Technical Features
- Semantic HTML5 markup
- ARIA labels for accessibility
- CSS custom properties (variables)
- Modular, well-commented code
- Form validation
- Mobile menu toggle
- Smooth scrolling
- Active navigation highlighting

## 🎨 CSS Architecture

The stylesheet is organized into 13 logical sections:

1. **CSS Variables & Root Styles**: Color palette, spacing, shadows
2. **Global Reset & Base Styles**: Normalize and base elements
3. **Layout & Container**: Grid and container utilities
4. **Header & Navigation**: Sticky header with smooth transitions
5. **Hero Section**: Gradient background with glassmorphism
6. **Buttons**: Reusable button styles
7. **Section Titles**: Consistent heading styles
8. **Solutions Section**: Service cards grid
9. **Packages Section**: Pricing cards with featured highlight
10. **Contact Section**: Form and contact details
11. **Footer**: Multi-column footer layout
12. **Responsive Design**: Mobile breakpoints
13. **Utility Classes**: Helper classes for common patterns

## 🚀 Getting Started

### Quick Start
Simply open `index.html` in a modern web browser.

### Development
1. Open the project folder in your code editor
2. Make changes to HTML, CSS, or JavaScript files
3. Refresh the browser to see updates

### Live Server (Recommended)
Use VS Code's Live Server extension for auto-reload:
```bash
# Install Live Server extension in VS Code
# Right-click on index.html → "Open with Live Server"
```

## 🎯 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🎨 Color Palette

```css
Primary: #545c66 (Gray-Blue)
Gradient: #545c66 → #2c6cb0
Background: #ffffff (White)
Section BG: #f5f5f5 (Light Gray)
Text: #333 (Dark Gray)
```

## 🔧 Customization

### Changing Colors
Edit CSS variables in `styles.css`:
```css
:root {
    --primary-color: #545c66;  /* Change this */
    --color-gray-light: #f5f5f5;
    /* ... more variables */
}
```

### Adding New Sections
1. Add HTML markup in `index.html`
2. Create corresponding styles in `styles.css`
3. Update navigation if needed

### Modifying JavaScript
All interactive features are in `script.js`:
- Mobile menu toggle
- Smooth scrolling
- Form validation
- Scroll animations
- Active nav highlighting

## 📝 Code Quality Features

### HTML
- ✅ Semantic HTML5 elements (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`)
- ✅ ARIA labels for accessibility
- ✅ Proper heading hierarchy
- ✅ Meta tags for SEO
- ✅ Open Graph tags for social sharing

### CSS
- ✅ CSS custom properties for maintainability
- ✅ Mobile-first responsive design
- ✅ BEM-inspired naming conventions
- ✅ Organized into logical sections
- ✅ Comprehensive comments

### JavaScript
- ✅ Modular function design
- ✅ Event delegation where appropriate
- ✅ No jQuery dependency (vanilla JS)
- ✅ Intersection Observer for performance
- ✅ Form validation

## 🚧 Future Enhancements

- [ ] Add loading animations
- [ ] Implement dark mode toggle
- [ ] Add testimonials section
- [ ] Create backend for contact form
- [ ] Add image gallery
- [ ] Implement live chat widget
- [ ] Add service area map
- [ ] Create blog section

## 📄 License

This project is available for use under standard commercial terms.

## 👨‍💻 Development Notes

### Performance
- No external dependencies (jQuery-free)
- Optimized animations using CSS transforms
- Lazy loading ready (can be added easily)
- Minimal JavaScript footprint

### Accessibility
- WCAG 2.1 AA compliant
- Keyboard navigation support
- Screen reader friendly
- Proper color contrast ratios

### Maintenance
- Well-commented code
- Consistent naming conventions
- Modular structure for easy updates
- CSS variables for quick theme changes

---

**Last Updated**: November 10, 2025  
**Version**: 2.0 (Refactored)
