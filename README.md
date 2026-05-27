# 🌿 Smart Carbon Tracker

> An interactive, single-page web application to log, visualise, and reduce your personal carbon footprint — tracking emissions from transport, energy, and food in real time.

🔗 **Live Demo:** [nityaa20.github.io/smart-carbon-tracker](https://nityaa20.github.io/smart-carbon-tracker) ← _update after deploying_


## ✨ Features

### 🔐 Authentication
- Sign in / Sign up screen with form validation
- Session managed in-browser (no backend required)

### 📊 Dashboard
- **Today's Emissions** — live kg CO₂ counter updated on every log entry
- **Weekly Average** — rolling daily average across all logged entries
- **Goal Progress Bar** — visual progress toward your weekly CO₂ target; turns red when exceeded
- **Eco Tip of the Day** — contextual sustainability advice card
- **Recent Entries Table** — last 5 logged entries with source-coloured badges
- **CSV Export** — download full emission history as a spreadsheet

### 📈 Analytics
- **Line chart** — trend of your last 8 emission entries
- **Doughnut chart** — breakdown by source (Transport / Energy / Food)
- **Weekly comparison bar chart** — this week vs last week
- **Transport pie chart** — Car / Bus / Bike/Walk split
- Time-range filter (7 days / 30 days / All time)

### 🌍 My Impact
- Monthly carbon debt displayed in kg CO₂
- Real-world equivalencies: km driven, smartphones charged, trees grown
- "Explore Offset Projects" CTA

### 👥 Community
- Weekly leaderboard with your rank highlighted
- Active community challenge (Green Commute Challenge)

### ⚙️ Settings
- **Dark / Light mode** toggle (persists via UI state)
- **Push notifications** — browser notification fires when weekly goal is exceeded
- **Set weekly CO₂ target** — personalised goal tracking
- **Reset all data** — permanent data wipe with confirmation dialog



## 🛠️ Tech Stack

| Layer        | Technology                          |
|--------------|-------------------------------------|
| Markup       | HTML5 — single file, zero build     |
| Styling      | CSS3 — custom properties, animations, responsive grid |
| Logic        | Vanilla JavaScript (ES6)            |
| Charts       | Chart.js v4                         |
| Icons        | Font Awesome 6.4                    |
| Fonts        | Google Fonts — Syne + DM Sans       |
| Notifications| Web Notifications API               |



## 🗂️ Project Structure

```
smart-carbon-tracker/
├── index.html          # Complete single-page app (HTML + CSS + JS)
├── docs/
│   └── screenshots/
│       └── dashboard.png   # Dashboard screenshot for README
├── .gitignore
└── README.md
```



## 🚀 Running Locally

```bash
# Clone the repository
git clone https://github.com/Nityaa20/smart-carbon-tracker.git
cd smart-carbon-tracker

# Open in your browser — no server needed
open index.html          # Mac
start index.html         # Windows
xdg-open index.html      # Linux
```

Or use **VS Code → Live Server** for hot reload during development.



## 🧮 Emission Factors Used

| Activity         | Factor              | Source basis         |
|------------------|---------------------|----------------------|
| Car              | 0.21 kg CO₂/km      | UK Dept. for Transport avg |
| Bus              | 0.10 kg CO₂/km      | Average public transport |
| Bike / Walk      | 0 kg CO₂/km         | Zero direct emissions |
| Electricity      | 0.50 kg CO₂/kWh     | Grid average estimate |
| Meat-based meal  | 5.0 kg CO₂/meal     | Food lifecycle studies |
| Vegetarian meal  | 2.5 kg CO₂/meal     | Food lifecycle studies |
| Vegan meal       | 1.0 kg CO₂/meal     | Food lifecycle studies |


## 🔮 Future Improvements

- [ ] Connect a real backend (Flask / Node) to persist data across sessions
- [ ] User authentication with secure sessions
- [ ] Monthly trend reports with downloadable PDF
- [ ] Location-based emission factors (India / UK / US grids differ significantly)
- [ ] Carbon budget planner — simulate impact of lifestyle changes
- [ ] Recurring entry templates (e.g. "daily commute")





[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/nityaa-suresh20/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/Nityaa20)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:nityaasuresh2005@gmail.com)
