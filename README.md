# LearnWise × Kraftshala — Website MVP

A responsive, browser-first website for interactive Meta Ads metric learning. This repository is the website only; there is no mobile-app project and no local development requirement.

## Current vertical slice
- Cover screen with Learn Mode CTA and Kraftshala link
- Intro screen with Take the Quiz CTA
- Impressions question with four options, disabled-until-selected submission, correctness feedback, and answer recording
- Impressions visual explanation
- Next: Reach question
- Reach question and visual explanation
- Responsive desktop/mobile styles and reduced-motion support

## Brand
- Navy: `#243E60`
- Yellow: `#F1AE13`

## Cloud deployment
The GitHub Actions workflow in `.github/workflows/deploy.yml` publishes `index.html` to GitHub Pages on pushes to `main`.

If Pages is not enabled automatically, open **Settings → Pages** and select **GitHub Actions** as the build and deployment source. Then check **Actions** for the deployment result.

## Scope notes
This is the first working vertical slice, not the complete 11-question course. The supplied PDF remains the source of truth for subsequent screens and content. The current explanation visuals are a responsive approximation and should be refined against the PDF references before the entire MVP is signed off.

## No local build
This is a static site. GitHub Actions handles deployment in the cloud; visitors use a browser. No Node.js toolchain is needed on a developer's laptop.
