# LearnWise × Kraftshala — Story-led Meta Ads learning website

A responsive, browser-first learning experience with recurring animated characters Maya (mentor) and Pixel (mascot). The project is website-only; source and deployments are managed through GitHub.

## Current build

- Story-style landing and mission briefing
- Twelve study chapters with character dialogue, concise teaching material, key takeaways, examples, and interactive mini-simulations:
  - Impressions
  - Reach
  - Frequency
  - Clicks (all)
  - Link Clicks
  - Unique Clicks (all)
  - Landing Page Views
  - Conversions
  - CTR
  - Conversion Rate (CVR)
  - CPM
  - CPC and CPA
- Character-led learning before the assessment
- Eight-step campaign journey activity with placement feedback
- Knowledge check with answer selection, positive/encouraging feedback, character reactions, hints, explanations and answer retention
- Score report computed from the learner's actual responses, with strong areas and areas to revisit
- Motion toggle, reduced-motion support, responsive layout and keyboard-focus styling

## Design

- Navy: `#243E60`
- Yellow: `#F1AE13`
- Original inline SVG character illustrations and speech bubbles
- No external image assets or runtime framework required for the current static build

## Cloud deployment

GitHub Actions publishes `index.html` to GitHub Pages when commits land on `main`.

- Repository: https://github.com/Himanshu615/learnwise-kraftshala
- Live site: https://himanshu615.github.io/learnwise-kraftshala/
- Deployment workflow: https://github.com/Himanshu615/learnwise-kraftshala/actions

All changes can be committed through GitHub. No local Node.js install is required.

## Source-content note

The source PDF calls for 11 scored questions while its screen sequence separately shows 12 metric question screens/concepts (Impressions, Reach, Frequency, Clicks all, Link Clicks, Unique Clicks all, Landing Page Views, Conversions, CTR, CVR, CPM, and CPC/CPA). This implementation currently teaches all 12 concepts and assesses each concept separately, so the score is calculated out of 12. Please validate whether you prefer the source's stated 11-question total or one scored comparison question combining two related metrics.

The eight-step user journey follows the source order: Impressions → Reach → Frequency → Clicks (all) → Unique Clicks (all) → Link Clicks → Landing Page Views → Conversions.
