# UniWAM project page deployment

This repository contains the static site at the `main` branch root.

## First-time setup

Open `https://github.com/Fysics-AI/uniwam.github.io/settings/pages`. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then click **Save**. Wait for GitHub to finish building before opening the published address below.

Published address: `https://fysics-ai.github.io/uniwam.github.io/`

The 33 full-length demo videos are hosted in the public Hugging Face dataset at `https://huggingface.co/datasets/KeliangLiu2025/UniWAM`. The site keeps local posters and uses the public video URLs in `assets/demos/manifest.json`.

To update the site, commit the changed files at the repository root and push `main`. GitHub Pages redeploys automatically. Do not commit the large source videos in `assets/demos/`.

The repository name `uniwam.github.io` does not make `https://uniwam.github.io/` available: that hostname belongs to the GitHub account named `UniWAM`. This repository's Pages address uses the owner name `Fysics-AI` and the repository name as the path.
