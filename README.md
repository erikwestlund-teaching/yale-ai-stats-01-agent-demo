# Exercise 1: Your First Agent

Part of the workshop **AI Tools for Statistical Programming and Analysis**. The prompts are on the workshop page.

A small analysis project: one messy data file and three notebooks for an AI agent to fill in.

## Install packages

Run this once in the R console, from the project folder:

```r
source("setup.R")
```

It installs any missing packages used anywhere in the workshop: readr, dplyr, tidyr, ggplot2, broom, here, and rmarkdown. If you already ran it for another workshop project, you can skip this step.

## Open the project

- **RStudio:** open `yale-ai-stats-01-agent-demo.Rproj`.
- **Positron or VS Code:** open this folder.
- **Claude Code or Codex:** start the tool from a terminal in this folder.

You need R and Quarto. Quarto comes with RStudio and Positron. `setup.R` installs the packages.

## Contents

```
inputs/raw/subgroup_estimates.csv   messy subgroup estimates
inputs/raw/codebook.md              what the columns mean
notebooks/01_cleaning.qmd           to be filled in by the agent
notebooks/02_summary.qmd            to be filled in by the agent
notebooks/03_analysis.qmd           to be filled in by the agent
```

Rendering a notebook writes its HTML to `outputs/notebooks/`, as set in `_quarto.yml`.

## Check the agent's work

- Read the code before you run it.
- Run the notebook yourself and confirm that it renders.
- Compare the results with the raw file. Check that the number of rows makes sense and that missing values were handled the way you would handle them.

## Folder layout

This project was created from a [Framework](https://framework.pub) blueprint, so it has the folder layout of a real analysis project: raw data in `inputs/raw/`, notebooks in `notebooks/`, and results in `outputs/`. You don't need the framework R package. The notebooks use plain R.
