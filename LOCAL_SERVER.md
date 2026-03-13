# Viewing the Site Locally

## Quick Start

From the project root (`triangulang/`), run:

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in your browser.

Press `Ctrl+C` to stop the server.

## Options

**Use a different port:**

```bash
python3 -m http.server 3000
```

**WIP sections (interactive demo, 3D viewer)** are hidden by default. To see them, add `?dev` to the URL:

```
http://localhost:8000?dev
```
