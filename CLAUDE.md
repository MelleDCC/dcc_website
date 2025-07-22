# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website for De CyberConsultant (DCC), a Dutch consultancy firm specializing in AI and cybersecurity services for SMEs (MKB). Built with pure HTML, CSS, and JavaScript without any frameworks or build tools.

**Company Details:**
- Active since 2021
- Target market: MKB (Small and Medium-sized Enterprises)
- Services: AI consulting/automation and Cybersecurity services
- Language: All content in Dutch (nl)
- Owners: Lev and Melle are both mede eigenaar (co-owners) who handle all aspects of the business

**Key Services:**
- AI Implementation and Automation
- Cybersecurity Consulting
- Phishing Simulation: AI-powered hyper-personalized and tailor-made phishing campaigns for security awareness training

## Development Commands

**Local Development:**
```bash
# Option 1: Open files directly in browser
open index.html

# Option 2: Simple HTTP server
python -m http.server 8000
```

**No build, test, or lint commands** - this is a static site with no tooling setup.

## Code Architecture

### File Structure
```
dcc_website/
├── index.html          # Landing page with split-screen AI/Cyber sections
├── ai.html            # AI services page (686 lines)
├── cyber.html         # Cybersecurity services page (504 lines)
├── contact.html       # Contact form page
├── style.css          # Single comprehensive stylesheet (4,766 lines)
└── *.png             # Company logo assets
```

### Key Design Patterns

**Split-Screen Landing:** The main page divides into AI (left) and Cybersecurity (right) sections, each expandable to full-screen immersive experiences.

**Visual Effects:**
- Canvas-based neural network animation for AI section
- Matrix-style falling characters for Cyber section
- Glass morphism effects with backdrop filters
- Smooth CSS transitions and hover states

**Color Scheme:**
- Background: White (#FFFFFF) 
- Text: Dark (#1D1D1F)
- AI accent: Blue themes
- Cyber accent: Red/matrix green themes

### Technology Stack
- **Pure HTML5/CSS3/JavaScript** - no frameworks
- **Google Fonts:** Inter, JetBrains Mono, Outfit
- **Canvas API** for animations
- **Modern CSS:** backdrop-filter, transforms, variables
- **Responsive design** with 768px mobile breakpoint

### Content Guidelines
- All text must be in Dutch
- Professional tone targeting business decision makers
- Focus on MKB/SME market segment
- Emphasize trust, expertise, and innovation

### Styling Conventions
- Single CSS file with all styles
- CSS custom properties for consistent theming
- Embedded JavaScript directly in HTML files
- Glass morphism achieved through backdrop-filter: blur()
- Mobile-first responsive approach

## Deployment

Hosted on **Vercel** as a static site - no server-side processing required.