# Florian Privat · Data Analyst

I turn player data into decisions: retention, A/B tests, monetisation and tracking quality.

- MSc Data Marketing Manager, INSEEC (2025–2026)
- Bachelor in Management & Business, Video Games & Esports, Gaming Campus Lyon (2021–2024)

**Tools:** SQL (DuckDB) · Python (pandas, SciPy, statsmodels, scikit-learn) · Power BI · Git and GitHub Actions

## Game analytics

### [game-event-analytics](https://github.com/DJ-Papy/game-event-analytics)

71 million events from a live mobile game over six weeks.

- 37% of new players come back the next day and 3% after two weeks. Players are lost between sessions, not in the first-session funnel (94.5% reach the first new zone).
- Rewarded video earns about twice as much per impression as interstitials. The ad A/B test had about 1,000 players per variant when about 9,400 were needed, so it could not conclude.
- Tracking plan built from the data: purchases logged on Android only, 10.4% of events without a session id, one missing day.

### [game-player-analytics](https://github.com/DJ-Papy/game-player-analytics)

Cookie Cats A/B test on 90,189 players: first gate at level 30 or at level 40.

- Moving the gate to level 40 lowers Day-7 retention by 0.8 points (p = 0.002); Day 1 is inconclusive. Recommendation: keep the gate at level 30.
- Segmentation checked against shuffled data: no usable structure, so no targeted offers built on it.

Both projects keep their SQL in versioned files and their logic in a tested Python package, run CI on every push, open each notebook with its answer, and end in a Power BI dashboard.

## Research

### [detection-desinformation-donnee](https://github.com/DJ-Papy/detection-desinformation-donnee) · MSc thesis, in French

Interpretable pipeline that checks the figures in French press articles against INSEE series (SDMX API). On 562 articles, about 1% of the figures could be compared directly with a dated official series. Tested, with CI, archived on Zenodo with a DOI.

---

All projects use public data. Open to Game Data Analyst roles · [LinkedIn](https://www.linkedin.com/in/florian-privat)
