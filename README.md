# 身心健康评估 · Wellbeing Survey

An interactive, single-page web app for self-assessment using three validated psychological scales.

**Live demo:** `https://teohsinyee.github.io/self-reflection-survey/`

## Scales included

| Scale | Full name | Items | Scoring |
|-------|-----------|-------|---------|
| **Ikigai-9** | Ikigai-9 Meaning in Life Scale | 9 | 1–5 per item, total 9–45 |
| **CBI** | Copenhagen Burnout Inventory | 13 (6 personal + 7 work) | 0/25/50/75/100, mean per subscale |
| **MLQ** | Meaning in Life Questionnaire | 10 | 1–7 per item, total 10–70 |

## Features

- Fully client-side — no data is sent to any server
- Real-time scoring as you answer
- Progress autosaves in your browser and restores after refresh
- Reverse-scored items handled automatically
- Interpretation labels shown after all questions are answered
- Exportable text summary for personal records or reflection
- One-click reset to start over
- Responsive, works on mobile and desktop

## How to deploy on GitHub Pages

1. Create a new GitHub repository (public)
2. Upload `index.html` to the root of the repo
3. Go to **Settings → Pages**
4. Under **Source**, select `main` branch and `/ (root)`
5. Click **Save** — your site will be live at `https://<username>.github.io/<repo-name>/`

## Local preview

Just open `index.html` directly in any browser — no build step or server needed.

## Privacy

All responses are processed entirely in the browser. No data is transmitted or logged anywhere. If autosave is available, answers are stored only in that browser's local storage until reset.

---

*For personal reflection and educational use only. For research or clinical use, please refer to the original validated instruments.*
