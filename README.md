# 🎮 Beast Games Analytics

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Streamlit](https://img.shields.io/badge/Streamlit-%23FE4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![Scipy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=white) ![YouTube](https://img.shields.io/badge/YouTube%20Data%20API%20v3-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)

**Data-driven content strategy intelligence for MrBeast's Beast Games** — connecting packaging decisions (thumbnails, titles, pacing, guests) to measurable performance outcomes.

## 🚀 [▶ Live Fan Engagement Demo](https://umair-tareen.github.io/beast-games-analysis/) &nbsp;|&nbsp; 📊 [▶ View Pitch Deck](https://umair-tareen.github.io/beast-games-analysis/pitch.html)
> Beast Games 3 Fan Engagement Intelligence Layer · 10-slide analytics pitch deck — no code required

---

## 📸 Dashboard Preview

![Beast Games Analytics Dashboard](assets/dashboard_preview.png)

> **9-tab interactive analytics suite** — channel intelligence, Amazon Prime Video viewership, word impact cloud, content opportunity matrix, fan engagement intelligence layer, and ops feedback loop. Built with Streamlit + Plotly.

---

## 💫 Project Overview

Beast Games is MrBeast's flagship entertainment show on Amazon Prime — the largest reality competition in YouTube history with 1,000 contestants and a $5M prize. This analysis identifies the data patterns behind its success by examining:

- **Thumbnail design** — Color psychology, composition, CTR impact
- **Title optimization** — Keywords, sentiment, urgency signals
- **Episode structure** — Pacing, retention curves, climax placement
- **Guest strategy** — Celebrity impact on views and engagement
- **Upload cadence** — Timing, frequency, series strategy

---

## 🔑 Key Findings

| Metric | Finding |
|--------|---------|
| Optimal title length | 6–9 words drives highest CTR |
| Best upload day | Thursday–Saturday shows 18% higher Day-1 views |
| Thumbnail dominant color | Red/high-contrast outperforms muted tones by ~22% |
| Retention cliff | Average 34% drop-off at 14–16 minute mark |
| Prize mention in title | +31% CTR lift vs. non-prize titles |
| Guest multiplier | Celebrity episodes average 2.1x view lift |
| Beast Games S2 Premiere | 8.5M viewers on Amazon Prime Video |

---

## 🧪 Key Hypotheses

1. Larger prize amounts in titles correlate with 25–35% higher CTR
2. Celebrity guest appearances drive 2–3x view lift
3. High-contrast thumbnail colors (Brand red) improve channel recognition by 15%
4. Critical retention drop-off occurs at the 15-minute mark (requires pacing adjustment)
5. Biweekly upload cadence optimizes audience anticipation vs. content fatigue

---

## 📊 Dashboard Tabs

| Tab | What it shows |
|-----|---------------|
| 📊 Dashboard | Avg views by episode type, engagement curves, retention |
| 📱 Platforms | Amazon Prime viewership, device breakdown, global markets |
| ✍️ Titles | Word impact cloud — bigger word = more views |
| 🎬 Structure | Episode type performance across all 3 channels |
| 👥 Guests | Guest vs. solo view multiplier analysis |
| ⏰ Uploads | Upload cadence and timing patterns |
| 🔮 Predictor | Content opportunity matrix + trend signal engine |
| 🎮 BeastBet | Fan Engagement Intelligence Layer — closed, non-monetary audience prediction system |
| 🔄 Ops Loop | Analytics → Ideation → Production feedback pipeline |

---

## ⚡ Quick Start

```bash
pip install -r requirements.txt
streamlit run dashboard.py
```

Opens at `http://localhost:8501`

> **Demo mode by default** — the dashboard ships with a curated channel dataset (`data/channels.yaml`) so it runs instantly with no API key. To pull live channel metrics, set a YouTube Data API v3 key and run the fetcher:
>
> ```bash
> export YOUTUBE_API_KEY='your_api_key'
> python3 fetch_youtube_data.py
> ```
>
> See [`YOUTUBE_API_SETUP.md`](YOUTUBE_API_SETUP.md) for setup details.

### Additional dashboards & CLI analysis

```bash
streamlit run results_dashboard.py    # YouTube data results view
streamlit run beastbet_dashboard.py   # Fan engagement prediction system
python3 analysis.py                   # Statistical insights framework
python3 ab_testing.py                 # A/B test analysis
python3 anomaly_detection.py          # Outlier detection engine
python3 competitive_analysis.py       # Competitor benchmarking
```

---

## 🔬 Methodology

### Data Sources
- YouTube Data API v3 — video metadata, view counts, engagement metrics (live mode)
- Curated channel dataset with estimated metrics for instant demo (`data/channels.yaml`)
- Amazon Prime Video Season 2 viewership data
- Cross-channel analysis: MrBeast (471M subs), MrBeast 2 (40M), Beast Philanthropy (26M)

### Stack
- **Python** — pandas, numpy, plotly, streamlit, scikit-learn, scipy
- **Data** — YAML-based channel data store + JSON analysis outputs
- **Dashboard** — Streamlit multi-tab with Plotly visualizations

---

## 💼 About This Analysis

This portfolio demonstrates applied YouTube intelligence — connecting content packaging decisions (thumbnails, titles, pacing, guests) to measurable performance outcomes. The analytical framework mirrors what a Senior Manager of YouTube Intelligence owns: defining which metrics matter, identifying patterns in clickability and watchability, and translating findings into actionable creative recommendations with measurable impact.

---

## 🌐 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/umairtareen/) [![TikTok](https://img.shields.io/badge/TikTok-%23000000.svg?logo=TikTok&logoColor=white)](https://www.tiktok.com/@quantify.life) [![X](https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white)](https://x.com/UAT_34) [![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?logo=github&logoColor=white)](https://github.com/umair-tareen)

*Built by Umair Tareen — Senior Manager, Data & Analytics*
