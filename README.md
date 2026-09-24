# VincyGreenGuard

A static environmental conservation landing page and community portal for tracking eco actions, reading sustainability content, and discovering local conservation events.

This project is a front-end-only website focused on climate and community engagement. It presents a polished green-themed experience for users interested in sustainability, local action, and environmental education.

## Overview

The site includes:
- a hero section with a conservation-focused mission statement
- feature cards highlighting eco actions, community, education, and events
- an action logger with sample recent activity entries and points
- a leaderboard for community participation
- blog/article cards about sustainability topics
- a forum section with sample community discussion posts
- an events section for upcoming environmental activities
- a contact form and auth modal flow for login/signup
- a dark-mode toggle and responsive mobile navigation

## Stack

- Primary language: HTML
- Styling: CSS
- Interactivity: JavaScript
- Deployment target: GitHub Pages (`https://vinycodepro.github.io/environment/`)

This is a lightweight static site rather than a full-stack application. There is no backend, database, or authentication service implemented in the repository yet.

## Project structure

```text
.
├── index.html            # main page structure and content sections
├── vincywebguard.css     # theme, layout, responsive design, modal styling
├── vincywebguard.js      # UI interactions (theme toggle, modal behavior, mobile menu)
├── README.mdgit          # stray git command log; not a usable project README
└── README.md             # project documentation (this file)
```

## Key implementation notes

### Front-end composition
- `index.html` defines the page sections and content for the full landing page.
- `vincywebguard.css` contains the design system, color palette, layouts, responsive rules, and modal styling.
- `vincywebguard.js` adds client-side behavior for:
  - theme toggling
  - login/signup modal switching
  - mobile menu toggle
  - smooth scrolling for in-page navigation
  - form submission mock alerts

### Main experience flow
The page is structured as a single-page environmental portal. A visitor can:
1. browse the mission and feature highlights
2. log a sustainability action in the tracker form
3. review recent eco activity and leaderboard rankings
4. browse educational blog content
5. read community forum posts and upcoming event cards
6. reach out through the contact form or account modal

## How to run

Because this is a static website, the simplest local workflow is:

```bash
cd environment
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

You can also open `index.html` directly in a browser, though a local HTTP server is preferred for consistent behavior.

## Best practices and improvement opportunities

This project is visually complete and polished for a landing page, but it currently behaves like a mockup. The largest opportunities are:

- connect forms to a real backend or API
- add persistent user accounts and eco action storage
- replace sample leaderboard and forum content with live data
- add real article/event detail pages
- implement server-side validation and sanitization
- create a proper deployment pipeline or CI checks

## Summary

VincyGreenGuard is a green-themed environmental community website built as a static HTML/CSS/JavaScript front-end. It is designed to showcase a sustainability platform with eco action tracking, community engagement, educational resources, and event discovery. The project is easy to run locally and is suitable as a prototype or GitHub Pages landing page.
