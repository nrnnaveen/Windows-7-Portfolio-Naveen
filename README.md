# Windows 7 Portfolio - Naveen

A Windows 7-style interactive portfolio website with desktop apps, start menu navigation, and portfolio sections rendered as in-window pages.

## Run locally

This is a static site, so you can run it with any local server.

### Option 1: Python

```bash
python3 -m http.server 8000
```

Then open: `http://localhost:8000`

### Option 2: VS Code Live Server

Open the project folder and run **Live Server** on `index.html`.

## Features

- Windows 7-like login and desktop shell
- Start menu app launcher and taskbar windows
- Embedded apps: Computer, Projects, Private Projects, Resume, Skills, Terminal, Calculator, Notepad, Paint, Task Manager, About, Contact, Recycle Bin
- External GitHub profile launch from the desktop environment

## Screenshots

- `docs/screenshots/login-screen.png` *(placeholder)*
- `docs/screenshots/desktop.png` *(placeholder)*
- `docs/screenshots/start-menu.png` *(placeholder)*
- `docs/screenshots/apps.png` *(placeholder)*

## GitHub Pages

To publish via GitHub Pages:

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (or your default branch), `/ (root)`
4. Save and wait for deployment.
5. Access your site from the Pages URL shown in Settings.
