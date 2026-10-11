# LearnWise × Kraftshala — Story-led learning website

A responsive, browser-first Meta Ads learning experience. The project is website-only; there is no mobile-app project and no local development requirement.

## Current build: first interactive vertical slice

- Premium responsive landing page with animated original SVG characters (Maya the mentor and Pixel the mascot)
- Story intro and mission framing before teaching begins
- A teaching-first Impressions lesson with an interactive ad-view slider and live impression/reach counters
- Friendly practice question shown after the lesson, with positive feedback, a hint, a retry-friendly tone, and no guilt-based scoring
- Explanation scene that connects impressions and reach
- A second teaching scene introducing Reach
- Motion toggle, reduced-motion support, responsive layouts, keyboard-focus styling, and accessible status feedback

## Brand

- Navy: `#243E60`
- Yellow: `#F1AE13`

## Cloud deployment

The GitHub Actions workflow in `.github/workflows/deploy.yml` publishes `index.html` to GitHub Pages on pushes to `main`.

- Repository: https://github.com/Himanshu615/learnwise-kraftshala
- Live site: https://himanshu615.github.io/learnwise-kraftshala/

All changes can be committed through GitHub and built/deployed in the cloud; no local Node.js installation is required for this static vertical slice.

## Next implementation phase

The complete MVP still needs the remaining source-PDF lessons and explanations, all 11 assessment questions, the draggable eight-step journey, and the final report calculated from the learner's actual answers. The supplied `MVP_LearnWise_Kraftshala.pdf` remains the source of truth for exact content and specified interactions. The current character illustrations are original inline SVG artwork, and the current learning flow is an initial vertical slice—not the finished course.
