# Teen Mental Health Analysis

An interactive Quarto dashboard exploring social media habits and mental health outcomes in teenagers.

## Prerequisites

- [R](https://cran.r-project.org/) (4.1 or later)
- [Quarto](https://quarto.org/docs/get-started/) (1.3 or later)
- The following R packages:

```r
install.packages(c("tidyverse", "plotly", "crosstalk", "viridis"))
```

## Data

Download the **Teen Mental Health Dataset** from Kaggle and place the CSV at:

```
~/Downloads/Teen_Mental_Health_Dataset.csv
```

The file path is hardcoded in the setup chunk of `Final_463.qmd`. If you save it elsewhere, update line 25 of that file to match.

## Running Locally

Render the dashboard from the terminal:

```bash
quarto render Final_463.qmd
```

This produces `Final_463.html` — a self-contained file you can open in any browser. No server required.

Alternatively, open `Final_463.qmd` in RStudio and click **Render**, or in VS Code with the Quarto extension installed.

## Project Structure

```
Final_463.qmd   # Source document — all code and prose
Final_463.html  # Rendered output (generated, not committed)
llm-log.md      # Log of AI-assisted changes made during development
README.md       # This file
```
