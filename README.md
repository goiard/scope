# SCOPE

> 🎓 A focused, local-first workspace for students to organize school, studying and progress.

<div align="center">

**A clean student dashboard for grades, exams, planning, focus and insights — without accounts, subscriptions or a backend.**

<img src="assets/dashboard-preview.webp" alt="SCOPE dashboard preview" width="100%">

</div>

## ✨ What is SCOPE?

SCOPE brings the parts of student life that usually live in different apps into one simple workspace.

It is built with semantic HTML, modern CSS and vanilla JavaScript, with academic data stored locally in your browser.

### 🧩 Everything in one workspace

| | Feature | What it does |
|---|---|---|
| 📊 | **Dashboard** | See your average, exams, study activity and today's plan at a glance |
| 📚 | **Subjects** | Manage courses, teachers and target grades |
| 📝 | **Grades** | Track grades and weighted averages |
| 📅 | **Exams** | Keep upcoming assessments and difficulty in one place |
| 🗓️ | **Planner** | Turn topics into structured study sessions |
| ⏱️ | **Focus** | Use Pomodoro, Deep Work or 52/17 sessions |
| 🧠 | **Quizzes** | Track practice and quiz performance |
| 📈 | **Analytics** | Understand focus time, completion and subject performance |
| 🗓️ | **Calendar** | View exams and planned study sessions by month |
| 🌍 | **Profiles** | Configure country, school type and year labels |
| 🌓 | **Themes** | Switch between light and dark modes |
| 💾 | **Data tools** | Export, import or reset your local workspace |

## 🔒 Privacy first

SCOPE is **local-first**.

- 🔐 Your academic data stays in your browser.
- 🚫 There is no SCOPE backend collecting your data.
- 💾 Export your workspace as JSON whenever you want.
- ♻️ Import a previous backup to restore it.
- ⚠️ Browser storage can still be cleared by the browser or device, so keep a backup if your data matters.

## 🛠️ Built with

- **HTML5** — semantic structure
- **CSS3** — responsive UI, animations and themes
- **Vanilla JavaScript** — application logic without a large framework
- **localStorage** — local-first data persistence
- **GitHub Actions** — automated GitHub Pages deployment

No Node.js, package manager or build step is required.

## 🚀 Run locally

```bash
git clone https://github.com/goiard/scope.git
cd scope
python -m http.server 8080
```

Then open **http://localhost:8080**.

You can also open `index.html` directly, although a local HTTP server is recommended for development.

## 📁 Project structure

```text
scope/
├── assets/
│   ├── dashboard-preview.webp
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

## 🌐 GitHub Pages

SCOPE is ready for static GitHub Pages hosting.

The repository includes a GitHub Actions workflow that deploys the site after pushes to `main`.

To enable it:

**Settings → Pages → Build and deployment → Source → GitHub Actions**

## 🎯 Development principles

SCOPE deliberately stays dependency-light.

- Keep dependencies close to zero.
- Keep the interface clean and predictable.
- Prefer semantic HTML and accessible controls.
- Keep academic data local unless a future feature explicitly needs a backend.
- Avoid unnecessary visual noise, gradients and decorative effects.
- Keep interactions fast on lower-end devices.
- Respect reduced-motion preferences.

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a focused branch.
3. Make the smallest coherent change.
4. Test locally in a current Chromium, Firefox or Safari browser.
5. Check desktop and mobile layouts.
6. Open a pull request with a concise explanation.

## 📄 License

SCOPE is licensed under the **MIT License**.

See [LICENSE](LICENSE).

Copyright © 2026 goiard.

---

<div align="center">

⭐ If you find SCOPE useful, consider giving the repository a star.

</div>
