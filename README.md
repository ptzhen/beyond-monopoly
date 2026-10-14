# Beyond Monopoly

An interactive Tableau story about how modern board games changed, alongside search interest in Malaysia. Created for FIT3179 Data Visualisation 1 (September 2026).

**[Explore the interactive dashboard on Tableau Public](https://public.tableau.com/app/profile/pierre.thian/viz/BeyondMonopolyDV1/BeyondMonopoly-Final)**

## The project

The dashboard brings together 1,853 top-ranked BoardGameGeek games released from 1990 to 2023 and Malaysian Google Trends data from 2006 to 2025. It follows changes in release volume, mechanics, themes, ratings, complexity and playing time, then looks at how search interest varies over time and across Malaysian regions.

## What stood out

- Solo and cooperative mechanics became much more common among the games in this sample, while auctions declined.
- Newer games in the sample have higher median ratings, but typical complexity and the share of games lasting more than two hours changed little.
- Malaysian search interest recovered after 2010 and varies by month and region. These data show parallel patterns; they do not establish that changes in game design caused the change in search interest.

## Explore or edit

The Tableau Public link is the best way to view the interactive version. To inspect the worksheets, calculations and data sources, download `Beyond_Monopoly.twbx` from this repository and open it in Tableau Desktop or Tableau Public. The packaged workbook includes the data extracts used by the dashboard.

## Data and limitations

- [Board Games Dataset: Complete Features](https://www.kaggle.com/datasets/chik0di/board-games-dataset-complete-features), a Kaggle dataset derived from BoardGameGeek. The visualisation analyses a top-ranked subset, so its patterns should not be treated as representative of every published board game.
- [Google Trends: “board game” in Malaysia](https://trends.google.com/explore?q=board%20game&date=all&geo=MY). Trends indices are relative search interest, not absolute search volume. Incomplete 2026 data were excluded.

Both sources were accessed on 31 August 2026. Analysis and visualisation by Pierre Thian.
