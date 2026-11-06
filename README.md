# Khaled Ali Elsayed — Portfolio

Personal portfolio website: plain HTML with Tailwind CSS (loaded from the Tailwind CDN). No build step.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole page: hero, projects, stack, education, contact |
| `khaled.jpg` | Profile photo |
| `Khaled_Ali_Elsayed_CV.pdf` | CV linked from the page |

## Run locally

Open `index.html` in a browser, or use the **Live Server** extension in VS Code (right-click `index.html` → Open with Live Server).

## Edit

Everything is in `index.html`. Search for the section comments: `<!-- Hero -->`, `<!-- Projects -->`, `<!-- Stack -->`, `<!-- Education -->`, `<!-- Contact -->`. Colors are the CSS variables at the top of the `<style>` block (light and dark values).
To update the CV, replace `Khaled_Ali_Elsayed_CV.pdf` and keep the same file name.

## Deploy (GitHub Pages)

1. Create a **public** repository named `KhaledAli1234.github.io`.
2. Push these files to the `main` branch.
3. Repository **Settings → Pages → Build and deployment**: Source `Deploy from a branch`, Branch `main`, folder `/ (root)`.
4. The site goes live at `https://khaledali1234.github.io`, usually within a minute.
