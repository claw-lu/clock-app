# Clock App

A minimal, full-screen clock web app with ambient background effects and timezone support.

## Features

- 24-hour time display (HH:MM:SS)
- Live seconds progress bar
- Animated ambient background orbs
- Timezone selector via hamburger settings panel (top-right)
- Dark theme with light theme support via `prefers-color-scheme`

## Tech Stack

- Node.js + Express (static file server)
- Vanilla HTML/CSS/JS (no frameworks)

## Getting Started

### Install dependencies

```
npm install
```

### Run locally

```
npm start
```

App runs at http://localhost:3000

## Project Structure

```
clock-app/
├── public/
│   └── index.html    # Single-page app (clock UI)
├── server.js         # Express static server
├── package.json
└── README.md
```

## GitHub

Repository: https://github.com/claw-lu/clock-app
