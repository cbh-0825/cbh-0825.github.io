# AI Agent Instructions for cbh-0825.github.io

## Project Overview

This is a **static GitHub Pages portfolio website** for 柏翰, showcasing a journey in programming, electronics, and natural sciences. The project contains:
- Single `index.html` file with embedded CSS (912 lines)
- Comprehensive `README.md` in Traditional Chinese (繁體中文)
- No build tools, dependencies, or deployment pipeline needed
- Deployed automatically via GitHub Pages

## Content & Structure

The website is organized in a single-page design with semantic HTML sections:

| Section | Purpose |
|---------|---------|
| **Hero** | Title, intro, call-to-action buttons, and profile stats |
| **About** | Personal philosophy and approach to learning |
| **Portfolio** | Showcase of projects in programming, Arduino, and science |
| **Skills** | Technical expertise across multiple areas |
| **Additional sections** | Contact, testimonials, or other custom content |

## Styling Conventions

The CSS uses a **CSS variable-based design system**:
- **Color palette**: `--bg`, `--bg-2`, `--bg-3` (backgrounds), `--accent`, `--accent-2`, `--accent-3` (highlights), `--text`, `--muted` (text colors)
- **Layout**: CSS Grid for large sections, Flexbox for components
- **Typography**: Responsive font sizes using `clamp()` for mobile-first design
- **Interactive elements**: Buttons use gradient backgrounds; hover effects use `transform` and `box-shadow`
- **Dark theme**: Deep blue/navy background with light text and cyan/turquoise accents

## Common Tasks

### Editing Content
1. Content is in Traditional Chinese (保留中文)
2. Update text directly in the `<h1>`, `<h2>`, `<p>`, or `<li>` elements
3. Ensure you preserve the semantic HTML structure and class names

### Adding New Sections
1. Add a new `<section>` element after existing sections
2. Use the same class pattern: `<section id="..." class="section">`
3. Follow the existing typography and spacing patterns
4. Apply `reveal` class to elements that use scroll-triggered animations

### Styling Changes
1. Modify CSS variables in the `:root` selector for theme-wide changes
2. Keep component styles scoped to their class (e.g., `.button`, `.card`)
3. Use `clamp()` for responsive font sizes (e.g., `font-size: clamp(1.6rem, 2vw, 2.2rem)`)
4. Test color changes against the dark theme for contrast

### Deployment
- Push to `main` branch and GitHub Pages will automatically deploy
- No build step required—changes go live after push

## Language & Tone

- **Language**: Traditional Chinese (繁體中文) — maintain consistency with existing content
- **Tone**: Academic yet personal, emphasizing curiosity, self-directed learning, and the connection between theory and practice
- **Audience**: Educators, potential collaborators, peers interested in STEM

## Project Interests to Understand

From the README, key areas of focus:
- **Programming languages**: Java (Oracle 1Z0-819 preparation), JavaScript, Python, C++
- **Electronics & Maker**: Arduino UNO, RC522 RFID modules, hardware-software integration
- **Natural science connection**: Understanding physics principles behind technology (e.g., Faraday's law and RFID)
- **Learning philosophy**: Hands-on experimentation, debugging as learning, understanding the "why" not just the "how"

## Tips for Working Efficiently

- No package.json, build tools, or dependencies—this is pure HTML/CSS
- Test changes in a browser by opening `index.html` locally
- The HTML is long but well-organized; use browser developer tools to inspect and locate elements
- Preserve accessibility (semantic HTML, ARIA labels, heading hierarchy)
- Changes are immediately visible when you reload—no build waiting
