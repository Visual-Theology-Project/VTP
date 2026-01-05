# Visual Theology Project

## Overview
A static HTML/CSS website for the Visual Theology Project. This is a simple portfolio-style site showcasing theological visual projects.

## Project Structure
- `index.html` - Main landing page
- `assets/style.css` - Global stylesheet
- `projects/` - Directory containing individual project pages
  - `sample-project.html` - Sample project page template

## Development
The site runs on a simple Python HTTP server on port 5000.

To run locally:
```bash
python -m http.server 5000 --bind 0.0.0.0
```

## Deployment
This is configured as a static site deployment. All files in the root directory are served directly.

## Recent Changes
- 2026-01-05: Initial Replit environment setup
