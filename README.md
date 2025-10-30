# MindfulCare  Mental Health page

MindfulCare is a simple, responsive mental-health template built with Bootstrap 5. It provides a calm layout for sharing resources, a quick (non-diagnostic) self-check, coping tips, and clear actions to find help.

This README focuses on the page (what it contains, how to preview locally, and where to edit content).

---

## Whats included

- `index.html`  Main page markup. Uses Bootstrap 5 via CDN and includes a small client-side self-check script.
- `assets/css/styles.css`  Minimal custom CSS (brand color, hero tweaks, small responsive rules).
- `.vscode/launch.json`  Optional VS Code launch settings (if you use the VS Code debugger/browser launcher).

## How to preview

From the project root (PowerShell recommended):

```powershell
python -m http.server 8000
# Then open http://localhost:8000 in your browser
```

Or open `index.html` directly in your browser. Using a local server is recommended for correct handling of some browser features.

## Page structure (quick guide)

- Navbar  responsive Bootstrap navbar with collapsed menu on small screens.
- Hero  primary messaging and CTAs (Find Resources, Try a Self-Check).
- About  short description of the page purpose.
- Resources  3 Bootstrap cards (Hotlines, Therapy, Self-Help Tools).
- Self-Check  two quick select questions with client-side, non-diagnostic feedback.
- Tips  short list of coping techniques.
- Footer  contact links and a short disclaimer.

## Editing content

- To change wording or links: edit `index.html`.
- To adjust visual styles: edit `assets/css/styles.css` (it loads after Bootstrap so you can override defaults).
- To add icons, illustrations or images: place files under `assets/images/` and update `index.html`.

## Accessibility & safety notes

- The page uses semantic sections and Bootstrap's accessible components. Continue to test with a keyboard and a screen reader.
- The self-check is for reflection only and is not a medical assessment. Add clear disclaimers if you collect/store any user responses and follow privacy best practices.

## Development & versioning

- I created a working branch named `workingbench` for the Bootstrap/layout work. Merge or open a Pull Request when ready.
- If you want an offline Bootstrap workflow, replace CDN links in `index.html` with local files or install Bootstrap via npm.

## Suggested next steps

- Convert the self-check result to use a Bootstrap Toast or Modal for clearer feedback.
- Add SVG illustrations (accessible with descriptive text) to improve visual clarity.

## Screenshots

Here are quick visual references of the page (generated mock screenshots). Replace these with real screenshots if you prefer — drop PNG/SVG files into `assets/screenshots/` and update the filenames below.

### Desktop

![Desktop screenshot](assets/screenshots/desktop.svg)

### Mobile (collapsed)

![Mobile screenshot](assets/screenshots/mobile.svg)


## License

No license is specified. Add a `LICENSE` file (for example MIT) if you want to open-source this project.

