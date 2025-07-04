# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

De CyberConsultant (DCC) website - a static HTML site showcasing AI and Cybersecurity consultancy services. The site features a split-screen design with immersive content sections for both service areas.

## Tech Stack

- Pure HTML/CSS/JavaScript (no framework or build tools)
- Google Fonts: Inter and JetBrains Mono
- No package manager or dependencies

## Project Structure

```
dcc_website/
├── index.html      # Main landing page with split-screen AI/Cyber sections
└── contact.html    # Contact page with team member information
```

## Development Workflow

### Running the Site
- Open HTML files directly in a browser
- Use any static file server (e.g., `python -m http.server`)
- No build or compilation step required

### Version Control
```bash
# Check status
git status

# Stage changes
git add .

# Commit with descriptive message
git commit -m "Description of changes"

# Push to GitHub
git push origin main
```

Repository: https://github.com/MelleDCC/dcc_website.git

## Code Architecture

### Design System
- **Color Palette**:
  - AI Section: #007aff (blue)
  - Cyber Section: #ff4757 (red)
  - Anthracite: #36454F
  - Background: #000033 (dark), white (light)

### Key Components

1. **Split-Screen Landing** (`index.html`):
   - Left: AI services with animated chat interface
   - Right: Cyber services with terminal-style UI
   - Both sections expand to immersive full-screen views

2. **Interactive Elements**:
   - CSS transitions for hover effects
   - JavaScript for section navigation
   - Typewriter effects for terminal UI
   - Animated metrics and progress bars

3. **Responsive Design**:
   - Mobile breakpoint at 768px
   - Vertical stacking on small screens
   - Touch-friendly interaction zones

### JavaScript Patterns
- Event listeners for navigation between sections
- Animation controls for typewriter effects
- State management via CSS classes (active/inactive states)

## Important Considerations

- All styles are inline within HTML files
- No external CSS or JS files to maintain
- Images should be optimized for web performance
- Ensure consistent color usage across pages
- Test animations on various devices for performance