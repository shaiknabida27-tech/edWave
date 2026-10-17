# EduWave – Learn Today. Grow Tomorrow.

Personalized learning for rural students: a gamified mental-math arena, free books and lessons,
career guidance after Class 10 / 12 (MPC, BiPC, Commerce, Arts), and spoken-English practice.

Everything runs in the browser from a single `index.html` file. No build step, no install.

## Features
- Home page, then a short setup (name, class, medium, interests)
- Personal dashboard with XP, levels, streak and badges
- Math Arena: 6 levels, lives, combos, stars and badges
- Free books and lessons, ordered by the student's interests
- Career guidance by stage and group (MPC, BiPC, Commerce, Arts)
- Speaking phrases with audio (browser text-to-speech)

## Note on the AI features
The AI English tutor, AI career counsellor and AI communication coach are built for Claude's
artifact environment. On GitHub Pages they show a "not connected" message. To enable them,
add a small backend that calls an AI API (keep the API key on the server, never in `index.html`).

## Run locally
Open `index.html` in any browser.

## Publish with GitHub Pages
1. Create a repository and upload `index.html` and `README.md`.
2. Go to Settings > Pages > Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. Your site appears at `https://<your-username>.github.io/<repo-name>/`.
