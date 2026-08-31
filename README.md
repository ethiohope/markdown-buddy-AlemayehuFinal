Markdown
# AI Assistance Declaration
- **AI Tools Used:** ChatGPT (GPT-4o) / Gemini 1.5 Pro
- **Date:** October 24, 2024
- **Prompts & Workflows:** Detailed in Appendix / Reflection.md
- **Manual Verification:** All code chunks, formulas, syntax, and outputs were manually executed and cross-checked in RStudio v2023.12 prior to commit.

---

# Retail Sales Performance Analytics (`sales_analysis.R`)

## Project Overview
This repository contains an end-to-end R data analytics workflow designed to evaluate retail store performance. The project ingests synthetic sales transaction data, calculates key performance metrics (total sales, average order value, and unit counts), identifies top-performing product categories, and exports cleaned summaries for executive reporting.

## Key Features
* **Data Cleaning & Preprocessing:** Handles missing values and standardizes date formats.
* **Exploratory Data Analysis (EDA):** Aggregates revenue trends across multiple product lines.
* **Automated Reporting:** Generates summary tables ready for visualization.

## Repository Structure
markdown-buddy-[yourname]/
├── README.md # Main project documentation
├── script_documentation.Rmd # R Markdown documentation of main analysis script
├── Reflection.md # AI usage disclosure, verification log, & reflections
└── data/
└── synthetic_sales.csv # Raw transaction data (synthetic)

## Installation & Dependencies
To run the analysis scripts in this repository, ensure you have **R (>= 4.2.0)** installed.

Install the required R packages by running the following command in your R console:

```r
install.packages(c("tidyverse", "knitr", "lubridate", "dplyr"))
