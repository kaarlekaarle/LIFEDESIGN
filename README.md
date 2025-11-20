# Life Design

A simple static website showcasing the work of Life Design, a creative collaboration between Leo Karhunen and Adam Tickle.

## Structure

- `src/pages/index.html` - Main page
- `src/styles/` - CSS files
- `src/assets/` - Images and fonts

## Running Locally

Serve the site using a simple HTTP server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000/src/pages/index.html` in your browser.

## Features

- Desktop: Hover over category words to view slideshows
- Mobile: Tap category words to view slideshows, tap anywhere to close
- Responsive design with mobile-first approach
- Dynamic viewport height support for stable mobile layout
