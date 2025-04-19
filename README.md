# danny.ink

A minimal personal landing page with an animated striped background and CSS blend-mode effects.

## Tech Stack

- **HTML/CSS** (static site)
- **Font:** Space Grotesk (Google Fonts)
- **Hosting:** Nginx (via Docker)

## Features

- Bold typographic design with layered scaling text and `mix-blend-mode: difference` for a dynamic visual effect
- Animated repeating stripe background using CSS keyframes
- Contact email and GitLab links
- Fully responsive viewport units for sizing

## Setup

Simply open `index.html` in a browser, or serve it with any static file server.

### Docker

```bash
docker build -t danny-ink .
docker run -p 80:80 danny-ink
```

The site will be available at `http://localhost`.

## Project Structure

```
index.html    # Landing page markup
style.css     # Styles, animation, and layout
Dockerfile    # Nginx Alpine container for deployment
```
