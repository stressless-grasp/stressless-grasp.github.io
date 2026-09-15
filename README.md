# StressLess project website

Anonymous project page for the double-blind review of **StressLess: Towards Generalizable Deformable and Fragile Object Grasping from Stress-Aware Demonstrations at Scale**.

## Local development

Use Node 24, then run:

```sh
npm ci
npm run dev
```

Open <http://localhost:4321/>. `npm run build` generates the static site in `dist/`, and `npm run preview` serves that build locally.

## Repository contents

- `src/pages/index.astro`: project description, method, results, and links.
- `src/styles/site.css`: responsive page styling.
- `public/assets/paper/stressless.pdf`: anonymized review manuscript.
- `public/assets/figures/`: project figures and browser-ready renders.
- `public/assets/video/`: highlight reel, full video, and poster image.
- `scripts/edit-video.sh`: reproducible FFmpeg edit for the 32-second highlight reel.
- `scripts/check-site.mjs`: browser checks for layout, assets, and interactions.

## GitHub Pages

The repository must be named `stressless-grasp.github.io` under the GitHub account or organization with the same name. The included workflow deploys every push to `main` through GitHub Actions. In the repository settings, select **GitHub Actions** as the Pages source.

The account or organization profile, repository metadata, commit identities, and public membership must also remain anonymous throughout double-blind review.

## Research assets

Research figures, manuscript, and video remain the property of the anonymous paper authors. No broad license is granted for these assets.
