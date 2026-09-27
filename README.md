# DATA 608 · Story 2 — Federal Reserve Mandates Over Time

CUNY SPS MS Data Science, Fall 2026 · Tage Singh

How the Fed has balanced its dual mandate (2% inflation, maximum employment) since 1995, and how explicit 2% targeting compares with Flexible Average Inflation Targeting (FAIT, Sep 2020 – Aug 2025).

| File | What it is |
|---|---|
| `story2_fed_mandate.qmd` | Quarto source (R). All chart code is inline. |
| `story2_fed_mandate.pdf` | Rendered report |
| `data/fred_macro_monthly.csv` | Monthly fed funds rate, unemployment rate, CPI-U, core CPI, core PCE (Jan 1993 – Aug 2026) |
| `data/fred_nrou_quarterly.csv` | CBO natural rate of unemployment (quarterly) |
| `story2_submission.zip` | The files above bundled for submission |

The .qmd reads the CSVs straight from this repo, so it renders anywhere with internet access:

```
quarto render story2_fed_mandate.qmd
```

R packages: tidyverse, patchwork, ggrepel, scales, zoo. Data source: FRED (BLS, Federal Reserve Board, BEA, CBO), retrieved 27 Sep 2026.
