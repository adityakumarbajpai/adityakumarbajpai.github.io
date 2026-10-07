# Aditya Kumar Bajpai: personal site

Two static pages and nothing else: no build step, no server code, no cookies, no analytics, no third-party requests.

| File | What it is |
|---|---|
| `index.html` | Resume |
| `projects.html` | Thirteen work projects |
| `Aditya-Kumar-Bajpai.pdf` | CV offered by the download button |
| `fonts/` | Self-hosted typefaces (SIL Open Font License) |

## Publish on GitHub Pages

1. Create a public repository. Name it `<your-username>.github.io` to serve at that address, or any name to serve at `<your-username>.github.io/<name>/`.
2. Upload every file in this folder to the repository root, keeping the `fonts` folder and the `.nojekyll` file.
3. In the repository: Settings, then Pages. Under "Build and deployment" choose "Deploy from a branch", branch `main`, folder `/ (root)`, and save.
4. The site is live a minute or two later.

## Preview on your own computer

Open `index.html` in a browser. Everything works from the file system.

## Update

Replace the changed file and commit. To change the CV, replace `Aditya-Kumar-Bajpai.pdf` with a file of the same name.
