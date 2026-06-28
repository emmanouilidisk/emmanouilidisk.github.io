# Easy-to-edit academic website

## Main file
- `index.html`

## Assets used by the page
- `bio3.jpg`
- `upenn_logo.png`
- `duth_logo.png`
- `research_opt.svg`
- `research_robust.svg`
- `research_ai.svg`
- `pub_certified.svg`
- `pub_rr.svg`
- `pub_ssd.svg`
- `pub_opinion.svg`

## How to edit
Open `index.html` in any text editor and search for these markers:
- `<!-- HERO SECTION -->`
- `<!-- RESEARCH MOTTO -->`
- `<!-- CONTACT BUTTONS -->`
- `<!-- ACADEMIC JOURNEY -->`
- `<!-- RESEARCH SECTION -->`
- `<!-- PUBLICATIONS SECTION -->`
- `<!-- HONORS SECTION -->`
- `<!-- SERVICE SECTION -->`
- `<!-- NEWS SECTION -->`

## How to run locally
In the folder with the files, run:
```bash
python3 -m http.server 8000
```

Then open:
```text
http://localhost:8000
```

## How to upload to GitHub Pages
1. Rename `easy_edit_index.html` to `index.html` if needed.
2. Go to your repository: `emmanouilidisk.github.io`
3. Upload `index.html` and all asset files to the root of the repository.
4. On GitHub, open `Settings -> Pages`
5. Under `Build and deployment` choose:
   - `Source`: Deploy from a branch
   - `Branch`: `main`
   - `Folder`: `/ (root)`
6. Wait a few minutes and visit:
   `https://emmanouilidisk.github.io`

## Recommended editing workflow
1. Edit locally
2. Refresh browser preview
3. Upload changed files to GitHub
4. Refresh the live site after GitHub finishes deploying
