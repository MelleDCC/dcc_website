# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website for De CyberConsultant (DCC), a Dutch consultancy firm specializing in AI and cybersecurity services. The site is built with vanilla HTML, CSS, and JavaScript - no frameworks or build tools are required.

### About De CyberConsultant

**Company**: De CyberConsultant  
**Active since**: 2021  
**Target market**: MKB (Small and Medium-sized Enterprises)

**Services**:
- **Cybersecurity**: Advies, trainingen, phishing simulaties, incident response planning
- **AI**: Advies, workshops, software op maat (agentic systems, tools, procesoptimalisatie)

**Website Purpose**: The website serves as an overview of services and contact information. It must convey professionalism and innovation through a super modern and smooth user experience.

## Development & Deployment

**Hosting**: The website runs on Vercel

**Local Development**:
- **To run locally**: Open any HTML file directly in a browser or use a simple HTTP server like `python -m http.server 8000`
- **No build commands**: The site requires no compilation or bundling
- **No tests**: No testing framework is configured
- **No linting**: No linting tools are set up

## Code Architecture

### File Structure
- `index.html` - Main landing page showcasing both AI and cyber services
- `ai.html` - Detailed AI services page
- `cyber.html` - Detailed cybersecurity services page  
- `contact.html` - Contact form page
- `style.css` - Single stylesheet containing all CSS (26KB)

### Key Design Patterns
1. **Modern CSS Effects**: The site uses glass morphism, backdrop filters, and CSS transforms extensively
2. **Color Scheme**: Recently migrated to a light theme with white background (#FFFFFF) and dark text (#1D1D1F)
3. **Navigation**: Fixed dashboard-style navigation with blur effects
4. **Responsive Design**: Mobile-first approach using viewport meta tags
5. **Page Transitions**: Vanilla JavaScript handles smooth scroll animations and page transitions

### Language
The website content is in Dutch (nl). All user-facing text should maintain this language consistency.

### Styling Conventions
- CSS variables are used for consistent theming
- Hover effects use transform and transition properties
- Glass effects achieved through backdrop-filter: blur()
- Gradient overlays for visual depth
- No external CSS frameworks - all styling is custom