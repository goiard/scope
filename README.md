# SCOPE

A clean, local-first student workspace for school, study and planning.

## What it includes

- Dashboard with grades, exams, daily study progress and focus activity
- Subjects with teachers and target grades
- Weighted grade tracking
- Upcoming exam management
- Study-plan generation
- Focus timer with Pomodoro, Deep Work and 52/17 modes
- Quiz tracking
- Analytics for focus time, completion and subject performance
- Calendar view for exams and study sessions
- Light and dark themes
- Responsive desktop/mobile navigation
- Country-aware school profiles
- JSON export/import backups
- No backend required — academic data stays in browser storage

## Run locally

SCOPE is a static web app and needs no build step.

    git clone https://github.com/goiard/scope.git
    cd scope
    python -m http.server 8080

Open http://localhost:8080.

## Project structure

    scope/
    ├── index.html
    ├── css/
    │   └── style.css
    ├── js/
    │   └── app.js
    └── README.md

## Data & privacy

SCOPE stores its workspace in browser local storage. Academic data is not sent to a SCOPE backend.

Use Settings → Export for a portable JSON backup and Settings → Import to restore one.

## Design goals

SCOPE stays dependency-light: semantic HTML, vanilla JavaScript and CSS. The interface uses restrained motion, SVG icons, responsive layouts and reduced-motion support instead of a heavy UI framework.

## Contributing

1. Fork the repository.
2. Create a focused branch.
3. Test the static app locally.
4. Open a pull request with a concise description.

## License

Add the license that matches how you want SCOPE to be distributed.
