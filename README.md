
# WebDev Browser Engine

A lightweight, browser-based development environment for building and testing HTML, CSS, and JavaScript.

## Features

- HTML, CSS, and JavaScript editors
- Live preview powered by the browser's native rendering engine
- Console output and error reporting
- Desktop, tablet, and mobile preview sizes
- Automatic local saving of editor code
- Export projects as a standalone HTML file
- Progressive Web App (PWA) manifest
- Service worker for offline caching
- Responsive dark emerald interface
- Champagne-gold accents

## Project Structure

```text
WebDev/
├── index.html
├── style.css
├── preview.html
├── manifest.json
├── sw.js
├── README.md
└── assets/
    ├── icon-192.png
    └── icon-512.png
```

## Getting Started

1. Open the published website over HTTPS.
2. Write HTML, CSS, and JavaScript in the editor.
3. Run your code to view the result.
4. Use Export HTML to save a standalone page.

## Technologies

- HTML5
- CSS3
- JavaScript
- Browser-native rendering engine
- Service Workers
- Progressive Web App APIs

## Storage

Editor code is saved in the browser's local storage. Clearing browser site data may remove saved projects.

## Limitations

WebDev is a browser-based coding environment, not a standalone Chromium browser engine. It uses the browser already running the application.

Offline support depends on successful initial caching and browser support.

## License

All rights reserved unless a license is added to this project.
