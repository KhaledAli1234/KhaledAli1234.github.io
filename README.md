# Khaled Ali Elsayed — Portfolio

Personal portfolio website. Plain HTML and CSS, no framework, no build step, no external requests (fonts are self-hosted).

## Files

| File | What it is |
|---|---|
| `index.html` | The whole page: hero, projects, skills, education, contact |
| `fonts/` | Self-hosted web fonts (Bricolage Grotesque, IBM Plex Sans, JetBrains Mono) |
| `khaled.jpg` | Profile photo |
| `Khaled_Ali_Elsayed_CV.pdf` | CV linked from the page |
| `favicon.svg` | Browser tab icon |

## Run locally

Open `index.html` in a browser, or use the **Live Server** extension in VS Code (right-click `index.html`, then **Open with Live Server**).

## Edit

Everything is in `index.html`.

- Content: search for the section comments `<!-- Hero -->`, `<!-- Projects -->`, `<!-- Skills -->`, `<!-- Education -->`, `<!-- Contact -->`.
- Add a project: copy one `<article class="project">` block inside the projects list and change the text.
- Colors: the CSS variables at the top of the `<style>` block (`--accent` is the one accent color; light and dark values are defined separately).
- CV: replace `Khaled_Ali_Elsayed_CV.pdf` and keep the same file name.

## Deploy (GitHub Pages)

1. Create a **public** repository named `KhaledAli1234.github.io`.
2. Push these files to the `main` branch.
3. Repository **Settings → Pages → Build and deployment**: Source `Deploy from a branch`, Branch `main`, folder `/ (root)`.
4. The site goes live at `https://khaledali1234.github.io`, usually within a minute. Every push to `main` updates it.
