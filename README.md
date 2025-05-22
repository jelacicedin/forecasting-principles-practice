# Forecasting: Principles and Practice (3rd Edition) - Practice Repository

This repository contains practical implementations, code exercises, and chapter-by-chapter notes based on the textbook:

**Forecasting: Principles and Practice (3rd edition)**  
by Rob J Hyndman and George Athanasopoulos  
Link to the book: [https://otexts.com/fpp3/](https://otexts.com/fpp3/)

## Structure

- `notebooks/`: R Markdown or Jupyter notebooks containing exercises and solutions for each chapter.
- `data/`: Contains raw and processed datasets used in the book (where permissible).
- `scripts/`: Utility R scripts for common functions.
- `renv/`: R environment snapshot to ensure reproducibility.

## Environment Setup

This project uses the `fpp3` suite and is managed with `renv` for reproducibility.

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/forecasting-principles-practice.git
cd forecasting-principles-practice
```
2. Restore R environment
Open R in the project directory and run:
```r
install.packages("renv")
renv::restore()
```
This will install all required packages (including fpp3, tsibble, feasts, fable, etc.).

Dependencies
R (>= 4.0)

fpp3

renv

tidyverse

License
This repository contains original work and code inspired by exercises in the open-access book. The book content itself is © Rob J Hyndman and George Athanasopoulos and is used only for educational purposes.

This repository is for self-study and personal mastery of time series forecasting using modern tools in R.
