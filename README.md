# 🐍 PyAnalytics — AI Interview Coach

> Practice Python Data Analytics interviews with AI-generated questions, instant evaluation, and live in-browser code execution.

![Made with Claude AI](https://img.shields.io/badge/Powered%20by-Claude%20AI-6366f1?style=flat-square&logo=anthropic)
![Python](https://img.shields.io/badge/Python-Pyodide%200.25-3776AB?style=flat-square&logo=python)
![License](https://img.shields.io/badge/License-MIT-10b981?style=flat-square)
![No Build](https://img.shields.io/badge/No%20Build%20Step-Zero%20Setup-f59e0b?style=flat-square)

---

## ✨ Features

- 🤖 **Claude AI** generates unique questions every session — no static question bank
- 📊 **10 Analytics Topics** — NumPy, Pandas, GroupBy, Matplotlib, Scikit-learn, Time-series & more
- 🎯 **4 Difficulty Levels** — Easy → Medium → Hard → Expert (auto-advances on strong performance)
- ▶️ **Live Python Execution** — run code directly in the browser via Pyodide (no server needed)
- 📝 **AI Evaluation** — scores your answer 0–100% with specific feedback and improvement tips
- 📈 **Session Dashboard** — score history, average, correct/partial/review breakdown
- 📱 **Mobile-first UI** — works on any modern browser, no install required

---

## 🚀 Live Demo

👉 **[yourusername.github.io/pyanalytics-quiz](https://vishalrshukla.github.io/pyanalytics-quiz)**

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| AI Questions & Evaluation | [Anthropic Claude API](https://anthropic.com) (`claude-sonnet-4-6`) |
| Python Runtime | [Pyodide 0.25](https://pyodide.org) (WebAssembly) |
| Frontend | React 18 (via CDN, no build step) |
| Hosting | GitHub Pages |
| Fonts | Inter + Fira Code |

---

## 📖 How to Use

1. Visit the [live demo link](#) above
2. Enter your [Anthropic API key](https://console.anthropic.com) when prompted
3. Choose a **difficulty level** and **topic**
4. Answer the AI-generated question in your own words or with code
5. Get instant AI feedback and a score
6. Run the correct solution in the live Python editor
7. Move to the next question — difficulty auto-increases as you improve!

> 🔐 Your API key is stored only in your browser's `sessionStorage` and is never sent anywhere except directly to `api.anthropic.com`.

---

## 🏗️ Deploy Your Own

This is a **single `index.html`** file — zero dependencies, zero build step.

```bash
# Clone
git clone https://github.com/yourusername/pyanalytics-quiz.git

# Open locally
open index.html    # macOS
start index.html   # Windows
```

Or deploy to GitHub Pages in 3 clicks:
`Settings → Pages → Branch: main / (root) → Save`

---

## 📚 Topics Covered

| # | Topic |
|---|---|
| 1 | NumPy arrays & vectorisation |
| 2 | Pandas DataFrames & Series |
| 3 | Data cleaning & missing values |
| 4 | GroupBy, pivot & merge |
| 5 | Matplotlib & Seaborn visualisation |
| 6 | Statistical analysis & hypothesis testing |
| 7 | Feature engineering |
| 8 | Scikit-learn ML pipelines |
| 9 | Time-series analysis |
| 10 | Performance optimisation & big data |

---

## 🙌 Built By

**Vishal Shukla** — VP, Data Analytics & Business Intelligence  
[LinkedIn](https://linkedin.com/in/vishal-r-shukla) · [Tableau Public](https://public.tableau.com/app/profile/vishal.shukla/vizzes#!/) 

---

## 📄 License

MIT — free to use, fork, and build upon.
