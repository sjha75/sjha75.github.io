# sjha75.github.io

Personal academic website of Shreya Jha, served by GitHub Pages.

## Editing

Everything is plain HTML and CSS — no build step.

- **Text** (bio, news, publications, projects): `index.html`
- **Colors and fonts**: the variables at the top of `style.css`
- **CV**: replace `assets/Shreya_Jha_CV.pdf` (keep the same file name)
- **Photo**: replace `assets/shreya.jpg` (a 4:5 portrait works best)

## Project figures

Drop files into `assets/projects/` with these names and they appear automatically.
Until a file exists, a placeholder is shown.

| Project | File |
|---|---|
| First-Order Trajectory Matching | `assets/projects/ftm.gif` |
| Solver2System | `assets/projects/solver2system.png` |
| Moment closures | `assets/projects/moment-closure.gif` |
| Electric-motor dynamics | `assets/projects/motor.png` |

To use a different file type, change the `src` of the matching `<img>` in `index.html`.
Keep GIFs under ~5 MB so the page loads quickly.

## Adding a news item or paper

Copy an existing `<li>` in the News or Publications list in `index.html` and edit it.
Commit and push; the site updates within a minute or two.
