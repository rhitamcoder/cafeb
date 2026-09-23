# ☕ Cafeb

**A static, hand-curated directory of remote-work-friendly cafes — built with plain HTML & CSS.**

Cafeb showcases a hand-picked list of cafes suited for remote work, each with details on wifi quality, outlet availability, noise level, seating style, and a short descriptive blurb. No backend, no database, no build step — just clean, semantic HTML and custom CSS, making it fast to load and simple to deploy anywhere.

---

## ✨ Features

- 📋 **Six curated cafe listings**, each with a name, location, and photo
- 🏷️ **At-a-glance tags** for wifi speed and outlet availability
- 🔇 **Noise & seating details** so you know what kind of work environment to expect
- 📝 **Descriptive blurbs** giving each cafe its own character and vibe
- 📱 Fully responsive card grid, from desktop down to mobile
- 🎨 Warm, coffee-shop-inspired theme (Lora + Inter fonts, CSS custom properties for easy re-theming)

---

## 🛠️ Tech Stack

- **HTML5** — semantic markup, no templating engine
- **CSS3** — custom styling with CSS variables, no framework
- **Google Fonts** — Lora (headings) & Inter (body)

---

## 📁 Project Structure

```
cafeb/
├── index.html          # Main (and only) page
├── style.css            # Stylesheet
├── assets/
│   ├── cafe1.jpg         # The Roasted Owl
│   ├── cafe2.jpg         # Brew & Bloom
│   ├── cafe3.jpg         # Steady Grind Coffee House
│   ├── cafe4.jpg         # The Quiet Cup
│   ├── cafe5.jpg         # Amber Leaf Cafe
│   └── cafe6.jpg         # Nomad's Nook
└── README.md
```

---

## ☕ Featured Cafes

| Cafe                        | Location                  | Best For                          |
|------------------------------|----------------------------|-------------------------------------|
| The Roasted Owl              | Downtown, Riverside District | Deep, focused work sessions       |
| Brew & Bloom                 | Garden Quarter              | Casual work, catching up on emails |
| Steady Grind Coffee House    | Old Mill Street             | Calls & meetings                   |
| The Quiet Cup                | Elm & 9th                   | Silent, library-like focus         |
| Amber Leaf Cafe              | Maple Row                   | Slower, relaxed work days          |
| Nomad's Nook                 | Harbor View                 | Remote workers & digital nomads    |

---

## ▶️ Getting Started

No installation or dependencies required — this is a static site.

```
git clone https://github.com/rhitamcoder/cafeb.git
```
```
cd cafeb
```

Then simply open `index.html` in your browser, or serve it locally with any static server, e.g.:

```
python -m http.server
```

### Deploying
Since this is a static site with no backend, it deploys easily on **GitHub Pages**, Netlify, or Vercel — just point the host at `index.html` in the repo root.

---

## ✏️ Adding a New Cafe

Since there's no database, new cafes are added directly in `index.html` by duplicating an existing `<article class="cafe-card">` block, updating its content, and dropping the corresponding photo into `assets/`.

---

## 🔗 Related Project

A dynamic, database-backed version of this same idea also exists — **[Brewbase](https://github.com/rhitamcoder/brewbase)** — built with Flask and SQLite, letting cafes be added and removed through a live web form instead of editing HTML directly.

---

## 📝 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.
