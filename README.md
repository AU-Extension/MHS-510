# MHS 510 Leadership and Organizational Behavior: course interactives

Interactive simulations for MHS 510 (Atlantis University). Each week has self-contained HTML pages: an explorer (Interactive A) and a scored challenge (Interactive B). The LMS blocks link to these pages through GitHub Pages.

Live site: https://au-extension.github.io/MHS-510/

## Structure

| Folder | Topic | Interactive A | Interactive B |
|---|---|---|---|
| week1 | Leading and managing in healthcare | leadership-styles-explorer.html | style-match-challenge.html |
| week2 | Individual behavior: personality, perception, and emotional intelligence | perception-replay-explorer.html | attribution-bias-challenge.html |
| week3 | Motivation, engagement, and retention | motivation-lab-explorer.html | engagement-rescue-challenge.html |
| week4 | Teams, communication, and the midterm memo | team-stages-explorer.html | sbar-handoff-challenge.html |
| week5 | Power, politics, conflict, and negotiation | conflict-styles-explorer.html | conflict-rounds-challenge.html |
| week6 | Organizational culture, structure, and change | change-steps-explorer.html | resistance-map-challenge.html |
| week7 | Decision making, ethics, and data-driven leadership | unit-scorecard-explorer.html | decision-bias-challenge.html |
| week8 | Leading yourself, developing others, and the final project | coaching-grow-explorer.html | executive-briefing-challenge.html |

The `data/` folder holds the fictional datasets used in the assignments, with a data dictionary in `data/README.md`.

## Publishing

1. Push this folder to the `main` branch of `AU-Extension/MHS-510`.
2. In the repository, open Settings, then Pages, and set Source to "Deploy from a branch", branch `main`, folder `/ (root)`.
3. Each page is then live at `https://au-extension.github.io/MHS-510/weekN/<file>.html`.

Every page loads the logo and GSAP and fonts from public CDNs, still works if GSAP fails to load, and needs no build step.
