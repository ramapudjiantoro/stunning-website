# CLAUDE.md — Stunning Website Project

## Identity
This is the **stunning-website** project — a premium creative agency portfolio built with modern HTML, CSS (Tailwind), and vanilla JavaScript. The site showcases "Apex Creative" with a high-end UI/UX design featuring smooth animations, interactive elements, and responsive layouts. Triggers: "stunning website", "apex creative", "stunning-website".

## Workflow
1. Keep HTML as the single source of truth for the live site
2. Maintain clean Git history with clear commit messages
3. Assets (images, fonts) load from CDN where possible
4. All styles embedded in the HTML file (no separate CSS files)
5. JavaScript is inline for simplicity and performance
6. Update index.html for any design or content changes
7. Push changes to GitHub after local testing

## Editorial Rules
- Keep the design premium and polished — no shortcuts on UX
- Preserve the color scheme: sky blue (#0EA5E9), sky light (#38BDF8), accent orange (#F97316), sky deep (#0C4A6E)
- Maintain fluid typography with clamp() for responsive scaling
- Use Archivo for headings, Space Grotesk for body text
- All animations follow the cubic-bezier(.16,1,.3,1) easing curve
- Form validation and accessibility are non-negotiable

## Resources
| File | Purpose | When to load |
|:---|:---|:---|
| `index.html` | Main website file | Always |
| `.gitignore` | Git exclusions | When updating repo |
| `README.md` | Project documentation | For contributors |
