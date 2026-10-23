# Chinese classroom

A static lesson library for teacher-led classes. Open `index.html`, choose a lesson, and use the home button in the lesson header to return to the chooser.

- `tania/index.html` — clothing design
- `liya/index.html` — renting and maintenance
- `ruslan/index.html` — rear-end collisions, beginner Chinese
- `rental-original/index.html` — the original Beijing rental task, preserved with its existing activities

Each lesson includes its own images, activities, and offline word help (pinyin, English, Russian). Liya's video is played separately by the teacher. Completion marks are stored in the current browser when local storage is available; they do not sync between devices. The top progress bar follows the current slide.

## Deploy (Netlify)

Settings are in `netlify.toml`: no build step, publish directory is the repo root. The existing site is https://chinese-lesson-13132.netlify.app/ . When this repo's `main` branch is connected to that Netlify project, pushes deploy automatically.

No framework, package installation, server, database, or SPA rewrite is required. Netlify's free plan supports this static setup, subject to the account's usage limits.

## Local use

Open `index.html` in a browser. The entire folder can also be downloaded for offline use; keep all four lesson folders next to the main `index.html` so the links work.
