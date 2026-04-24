# Teach Yourself Deep Learning

A static GitHub Pages site for an opinionated deep learning curriculum, modeled after the compact TeachYourselfCS layout.

## Local preview

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages

This repo is ready for GitHub Pages through the included workflow:

1. Push the repository to GitHub.
2. In the GitHub repository, go to `Settings -> Pages`.
3. Set `Source` to `GitHub Actions`.
4. Push to `main`; `.github/workflows/pages.yml` deploys the static files.

There is no framework build step. The workflow uploads the repository root as a static Pages artifact.
