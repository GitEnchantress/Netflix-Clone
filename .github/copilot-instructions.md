# Netflix Clone - AI Coding Guidelines

## Project Overview
This is a pure HTML/CSS Netflix landing page clone built for learning purposes. No JavaScript frameworks or build tools are used - just vanilla HTML and CSS.

## Architecture Patterns

### File Structure
- `index.html` - Main landing page with banner and navigation
- `style.css` - All styling with CSS custom properties and responsive design
- `assets/` - Static images (logo, background, icons)

### CSS Conventions
- Use CSS custom properties (variables) for theming: `--btncolor: #f62707`
- Apply universal reset: `* { margin: 0px; padding: 0px; }`
- Use `font-family: 'Poppins', sans-serif` globally
- Background overlays with `linear-gradient(rgba(...), rgba(...)), url(...)`

### Responsive Design
- Mobile-first approach with `@media (max-width: 600px)` breakpoints
- Flexbox layouts for navigation and content containers
- Adjust font sizes, margins, and flex directions for mobile

### HTML Structure
- Semantic elements: `<main>`, `<section>`, navigation in `<nav>`
- Custom button elements: `<btn class="sign-in-btn">` (not semantic `<button>`)
- Class naming: descriptive like `.navbar`, `.container`, `.banner`

### Asset Management
- Images stored in `assets/` directory
- Background images referenced via CSS `background-image: url('assets/...')`
- Logo and icons as `<img>` elements

## Development Workflow
- Open `index.html` directly in browser (no build step required)
- Edit CSS in `style.css` for styling changes
- Add new sections by extending HTML structure and corresponding CSS classes

## Code Style
- Indentation: consistent spacing (4 spaces apparent)
- CSS properties grouped logically (layout, colors, typography)
- Placeholder styling with `::placeholder` pseudo-element
- Cursor styles: `cursor: pointer` for buttons, `cursor: grab` for interactive elements