# STAT184_HW4.3

This repo has my work for HW #4.3 in Stat 184 at Penn State: My First Reproducible Data Analysis.

## What's in here
- `HW4.3_Bathija.qmd`: the Quarto file I used to make my report
- `HW4.3_Kabir_Bathija-2.pdf`: the PDF I submitted for HW #4.3
- `plan.md`: my plan for setting up the repo and doing the assignment
- `README.md`: this file

## What the report covers
1. Summary stats tables of diamond length, width, and depth by clarity
2. My Big 10 Academic Alliance Love Data Week plot (NCAA women's basketball three-point % vs. win %)
3. Monte Carlo numerical integration of a Weibull PDF
4. A comparison of a plan-based genAI prompt vs. a generic prompt using the relig_income data
5. A reflection on what I've learned so far

## How to reproduce
Open the QMD in RStudio and click Render. You'll need these packages:
- {tidyverse} (dplyr 1.2.0 or newer, since I used `filter_out()`)
- {knitr}
- {kableExtra}

The BTAA section reads `team_box.csv`, so that file needs to be in the same folder as the QMD.

## Author
Kabir Bathija
