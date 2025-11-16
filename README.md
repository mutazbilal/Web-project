# Smart Academic Assistant (SAA) — Frontend (Phase 1)

This folder contains a simple, beginner-friendly static frontend for the Smart Academic Assistant (SAA) project.

Files included:

- `index.html` — Dashboard page (Predicted Score, Risk Level, Priority Tasks, Chart placeholder)
- `tasks.html` — Task Manager page (static form + sample task cards)
- `performance.html` — Performance Predictor page (input fields + placeholder results)
- `analytics.html` — Analytics Dashboard (placeholder chart boxes)
- `styles.css` — Single stylesheet used by all pages

How to preview

1. Open the main page directly in your default browser (Windows PowerShell):

```powershell
Start-Process -FilePath (Resolve-Path ".\index.html")
```

2. Or run a simple local HTTP server from the `web pro` folder (recommended if you plan to load external fonts reliably):

```powershell
# change into the folder first
Set-Location -Path ".";
# if you have Python 3 installed
python -m http.server 8000;
# then open http://localhost:8000 in your browser
```

Notes

- The UI is static: there is no JavaScript or backend logic. Buttons and forms are placeholders for the next development phase.
- The CSS uses the Google `Poppins` font via an `@import`. If the font does not load, the system fallback fonts will be used.
- All pages are linked together using relative links; you can open any page directly.

If you want any visual tweaks (colors, spacing, fonts) or a small local preview script, tell me which change you'd like and I can update the files.
