# Plan for STAT184_HW4.3

## Goal
Set up and keep up a public GitHub repo for HW #4.3 that shows my work using version control, and build a reproducible Quarto report that pulls together my Stat 184 work.

## Subgoals
- Step 1: Create the repo and set up the main and dev branches.
- Step 2: Use Issues to track what still needs to get done.
- Step 3: Build the HW #4.3 Quarto document (diamonds tables, BTAA plot, Monte Carlo integration, genAI comparison, and reflection).
- Step 4: Upload my files on the dev branch with clear commits.
- Step 5: Merge dev into main with a pull request that closes my issues.

## Needs
*Nouns:* GitHub account, public repo, main branch, dev branch, issues, commits, pull request, README, plan file, QMD file, PDF, {tidyverse}, {knitr}, {kableExtra}, diamonds data, NCAA team box score data, relig_income data

*Verbs:* creating, branching, opening (issues), assigning, writing, coding, rendering, uploading, committing, reviewing, merging, closing

## Steps

### Repo
1. Create a public repo called STAT184_HW4.3 with a README, then make a dev branch off of main so main only gets finished work.
2. Open two issues (one for uploading my HW files, one for the README and plan) and assign them to myself.
3. Upload my PDF and QMD to dev, then add this plan and finish the README, with each change in its own commit that mentions the issue number.
4. Open a pull request from dev into main that says "Closes #1" and "Closes #2", then merge it so both issues close.
5. Check that the repo is public by opening it in a private window, then submit the link.

### HW #4.3
1. Set up the Quarto YAML for a PDF and load {tidyverse}, {knitr}, and {kableExtra}.
2. Remove diamonds with a 0 dimension, pivot longer, and make three tables of summary stats by clarity.
3. Wrangle the NCAA team box scores into one row per team per season and plot three-point % vs. win %, with the Big Ten and Penn State highlighted.
4. Write a Monte Carlo function for the Weibull PDF (shape 1.5, scale 1), run it at n = 10, 100, 1,000, and 10,000, and show the results in a small multiple.
5. Write a plan for relig_income, compare the plan-based prompt with a generic prompt, write my reflection, and render to PDF.
