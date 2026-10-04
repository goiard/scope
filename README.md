# SCOPE

> A focused, local-first workspace for students to organize school, studying and progress.

SCOPE is a dependency-light static web app built with semantic HTML, CSS and vanilla JavaScript. It keeps academic data in the browser and gives students one place for subjects, grades, exams, study sessions, focus time and insights.

## Features

- **Dashboard** — current average, next exam, daily plan and focus activity
- **Subjects** — teachers, target grades and course overview
- **Grades** — weighted grade tracking and average calculation
- **Exams** — upcoming assessments with difficulty indicators
- **Planner** — generate repeatable study sessions around a topic
- **Focus** — Pomodoro, Deep Work and 52/17 timers with session history
- **Quizzes** — lightweight practice-set tracking
- **Analytics** — focus time, completion and subject performance
- **Calendar** — exams and planned sessions in a monthly view
- **Profiles** — country-aware school types and year labels
- **Themes** — light and dark modes
- **Data tools** — JSON export/import and full local reset
- **Responsive UI** — desktop sidebar and mobile navigation
- **Accessibility-minded UI** — keyboard-friendly controls and reduced-motion support

## Privacy

SCOPE is local-first. Your workspace is stored in browser local storage and there is no SCOPE backend collecting your academic data.

Use **Settings → Export** to create a JSON backup. Use **Settings → Import** to restore one.

> Note: browser storage can be cleared by the browser or device. Keep an exported backup if your data matters.

## Run locally

No Node.js, package manager or build step is required.

```bash
git clone https://github.com/goiard/scope.git
cd scope
python -m http.server 8080
```

Then open **http://localhost:8080**.

You can also open `index.html` directly, although a local HTTP server is recommended for development.

## Project structure

```text
scope/
├── assets/
│   └── icon.svg
├── css/
│   └── style.css
├── js/
│   └── app.js
├── .github/
│   └── workflows/
│       └── pages.yml
├── index.html
├── manifest.webmanifest
├── LICENSE
└── README.md
```

## GitHub Pages

SCOPE is ready to deploy as a static GitHub Pages site. The repository includes a GitHub Actions workflow that publishes the site after pushes to `main`.

In GitHub, set **Settings → Pages → Build and deployment → Source** to **GitHub Actions**. GitHub's current Pages workflow uses the Pages configuration, artifact upload and deployment actions for this setup. 

## Development principles

SCOPE deliberately avoids a large framework for a small static application.

- Keep dependencies close to zero.
- Keep UI components reusable and predictable.
- Prefer semantic HTML and accessible controls.
- Keep data local unless a future feature explicitly requires a backend.
- Avoid unnecessary visual noise, gradients and decorative effects.
- Keep interactions fast on low-end devices.

## Contributing

1. Fork the repository.
2. Create a focused branch.
3. Make the smallest coherent change.
4. Test the app locally in a current Chromium/Firefox/Safari browser.
5. Check desktop and mobile layouts.
6. Open a pull request with a concise explanation of the change.

## License

SCOPE is licensed under the **MIT License**. See [LICENSE](LICENSE).

Copyright © 2026 goiard.
