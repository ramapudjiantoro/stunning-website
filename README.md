# Apex Creative — Stunning Website

A premium creative agency portfolio website built with modern web standards. Single-file HTML architecture with embedded styles and scripts for rapid deployment and minimal dependencies.

## Features

- **Responsive Design** — Works seamlessly on mobile, tablet, and desktop
- **Smooth Animations** — Reveal effects, scroll animations, and interactive hover states
- **Custom Cursor** — Desktop-only animated cursor with expanding ring
- **Performance** — Single HTML file, Tailwind via CDN, optimized assets
- **Accessibility** — Semantic HTML, ARIA labels, keyboard navigation
- **Modern UX** — Glassmorphism cards, gradient text, fluid typography

## Tech Stack

- **HTML5** — Semantic markup with accessibility in mind
- **Tailwind CSS** — Utility-first styling via CDN
- **Vanilla JavaScript** — No frameworks, pure ES6+
- **Google Fonts** — Archivo (headings), Space Grotesk (body)

## File Structure

```
stunning-website/
├── index.html          # Single source of truth
├── .gitignore
├── README.md
├── CLAUDE.md           # Project instructions
├── MEMORY.md           # Project notes & decisions
└── ARCHIVE.md          # Archived entries
```

## Quick Start

1. Clone the repository
2. Open `index.html` in a modern browser
3. No build step required — works immediately

## Customization

All styles and configuration are in `index.html`:

- **Colors** — Edit the Tailwind config in `<script>` tags (lines 13–32)
- **Fonts** — Modify Google Fonts link in `<head>` (line 9)
- **Content** — Update HTML sections directly
- **Animations** — Adjust CSS transitions and keyframes in `<style>` (lines 35–277)

## Deployment

Simply deploy the single `index.html` file to any web host:
- Netlify: Drag & drop the file
- GitHub Pages: Push to repository
- Any static host: Copy the file

## Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Android)

## Project Status

✅ Initial launch complete  
📋 See MEMORY.md for active tasks and decisions

## License

2026 Apex Creative Studio. All rights reserved.
