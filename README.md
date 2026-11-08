# Absurdities

The organization's website at https://absurdities.github.io/.

Plain HTML and CSS. No dependencies, JavaScript, external fonts, or build step.

## Add a project

1. In `index.html`, remove the `empty-state` block when adding the first project.
2. Copy the commented `project` entry and update its URL, number, name, and description.
3. Remove the entry's comment markers.
4. Update the visible project count and its `aria-label`.
5. Commit and push to `main`. GitHub Pages publishes the repository root.

## Visual identity

The selected impossible triangle uses parchment gold on near-black. The original
PNG is `assets/logo.png`; `assets/mark.webp` is its optimized website version.
The original logo was created with the built-in image generation tool and
selected by the organization owner. The favicon is a small copy of that logo.

Colors and responsive layout rules are in `style.css`.

## Local preview

Run `python3 -m http.server 8000`, then open http://localhost:8000/.
