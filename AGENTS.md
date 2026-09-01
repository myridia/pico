# AGENTS.md — pico

## What this is
Pico.css demo site showcasing a pure-CSS off-canvas navigation pattern with light/dark/auto theme switching, no JavaScript required.

## Stack
- HTML/CSS (Pico.css framework)
- Docker (nginx)

## Build
```bash
cd dockers && docker-compose up
```

## Run
Access via `http://127.0.0.1` after docker-compose up.

## Structure
- `public/index.html` — main demo page with off-canvas nav
- `public/liquid.html` — liquid layout demo
- `public/css/pico.min.css` — Pico CSS framework
- `dockers/docker-compose.yml` — nginx setup
- `ask.sh` — task menu

## Conventions
- No comments in code unless asked.
- No JavaScript used — pure CSS patterns only.
- Verify: `bash -n ask.sh`
