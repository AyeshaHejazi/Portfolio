# 🌐 Ayesha Hejazi — Personal Portfolio

> Live portfolio website built with pure HTML, CSS & JavaScript. No frameworks. No dependencies. Just code.

[![Live Site](https://img.shields.io/badge/Live%20Site-ayeshahejazi.github.io-00d4ff?style=flat-square&logo=github)](https://ayeshahejazi.github.io)
[![Made With](https://img.shields.io/badge/Made%20with-HTML%20%7C%20CSS%20%7C%20JS-0d47a1?style=flat-square)](https://github.com/AyeshaHejazi/AyeshaHejazi.github.io)
[![GitHub API](https://img.shields.io/badge/Data-Live%20GitHub%20API-00ff88?style=flat-square&logo=github)](https://api.github.com/users/AyeshaHejazi)

---

## ✨ Features

- **5 pages** — Home, About, Skills, Projects, Contact
- **Live GitHub data** — stats, repos, and language usage auto-update via GitHub API
- **Animated particle canvas** background with mouse interaction
- **Custom glowing cursor**
- **Keyboard navigation** — use ← → arrow keys to switch pages
- **Fully embedded** — single HTML file, no external assets needed
- **Dark navy + electric blue** theme

---

## 📸 Preview

| Home | Projects |
|------|----------|
| Animated hero with live GitHub stats | Auto-fetched repos with live "updated" timestamps |

---

## 🛠️ Tech Stack

```
HTML5 · CSS3 · Vanilla JavaScript · GitHub REST API · Canvas API
```

---

## 🚀 How to Run Locally

No setup needed. Just open the file:

```bash
# Clone the repo
git clone https://github.com/AyeshaHejazi/AyeshaHejazi.github.io.git

# Open in browser
open index.html
```

---

## 📡 Live GitHub API

The portfolio fetches live data from the GitHub API on every visit — no API key required for public data:

```
GET https://api.github.com/users/AyeshaHejazi
GET https://api.github.com/users/AyeshaHejazi/repos
GET https://api.github.com/repos/AyeshaHejazi/{repo}/languages
```

Stats that auto-update:
- ✅ Repository count
- ✅ Followers & Following
- ✅ Total stars earned
- ✅ Project list with descriptions
- ✅ Language usage percentages

---

## 📁 File Structure

```
AyeshaHejazi.github.io/
└── index.html      ← entire portfolio (self-contained)
└── README.md       ← this file
```

---

## 🔧 Customization

To update your photo, open `index.html` and search for `data:image/jpeg;base64,` — replace the long string after it with your new photo's base64 encoded version.

To update bio text, search for `<!-- ABOUT -->` in the file and edit the paragraph tags directly.

---

## 📬 Contact

- 🌐 [Portfolio](https://ayeshahejazi.github.io)
- 💼 [LinkedIn](https://www.linkedin.com/in/ayeshahejazi)
- 🐙 [GitHub](https://github.com/AyeshaHejazi)
- 🐘 [Mastodon](https://mastodon.social/@Ayesha)

---

<p align="center">Crafted with 💙 by Ayesha Hejazi · Delhi, India</p>


