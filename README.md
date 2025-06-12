# 📈 EPFL - Investments Project - Spring 2025

**Course instructors**: Pierre Collin-Dufresne & Florian Perusset  
**Group members**:
- Adrien Aït Lalim (SCIPER 326588) - [@0marp](https://github.com/0marp)
- Matthias Wyss (SCIPER 329884) - [@matthias-wyss](https://github.com/matthias-wyss)
- Liess Gröli (SCIPER 327521) - [@Lsgrli](https://github.com/Lsgrli)
- Massimo Berardi (SCIPER 345943) - [@Mass-14](https://github.com/Mass-14)

---

## 🗂 Project Structure

This repository contains the full solution to the EPFL Investments Project for the Spring 2025 course. The goal was to evaluate the benefits of international diversification and dynamic portfolio strategies using equity indices and currencies.

```
.
├── notebook.ipynb                      # Main notebook with all code, plots, and results
├── investments-project-report.pdf      # Written report answering all questions
├── investments-project-guidelines.pdf  # Official project instructions and questions
├── .gitignore                          # Ignore temporary files, datasets, and outputs
├── data/                               # Contains input datasets and intermediate results
│   ├── fama-french-5factors/           # Fama-French 5 factor data (used in Q9)
│   ├── monthly_exchange_rate/          # Monthly exchange rate data
│   ├── monthly_returns/                # Equity index returns
│   ├── preprocess/                     # Intermediate preprocessed files
│   ├── q3/                             # Processed outputs for Q3
│   ├── q4/                             # Momentum strategy outputs
│   ├── q5/                             # Long-term reversal strategy outputs
│   ├── q6/                             # Currency carry strategy outputs
│   ├── q7/                             # Dollar strategy outputs
│   └── three_month_interbank_rate/     # Interest rate data from FRED
```

We stored intermediate CSV files after each step to reuse them efficiently in subsequent questions.

---

## 📋 Project Summary

We built and analyzed several strategies:

1. **International Diversification (DIV)** - Based on equal-weighting, risk parity, and mean-variance optimization of international equity indices (hedged/unhedged).
2. **Momentum (MOM)** - Long-short strategy based on 11-month momentum in currency-hedged equity indices.
3. **Reversal (REV)** - Contrarian strategy based on 5-year past returns.
4. **Carry (CARRY)** - Currency strategy based on interest rate differentials.
5. **Dollar (DOLLAR)** - A long-USD strategy versus a basket of foreign currencies.
6. **Optimal Fund Allocation (STRAT)** - Combining DIV with the four alternative strategies under a 15% volatility target.
7. **Risk Analysis** - Regression of the fund strategy returns on the Fama-French 5 factors.

All analysis was implemented in Python, and all results are reproducible using the provided notebook.

---

## ⚠️ Notes

- The project was submitted after the course had ended, hence WRDS access was no longer available. All necessary data was downloaded prior to the June 4 deadline.
- All code and answers are included in `notebook.ipynb`.
- The final written report is available under `investments-report.pdf`.
- The official project instructions are provided in `investments-project-guidelines.pdf`.

---

## 🧪 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

---

## 📧 Contact

For any questions about the repository or analysis:

- [Adrien Aït Lalim](https://github.com/0marp)
- [Matthias Wyss](https://github.com/matthias-wyss)
- [Liess Gröli](https://github.com/Lsgrli)
- [Massimo Berardi](https://github.com/Mass-14)
