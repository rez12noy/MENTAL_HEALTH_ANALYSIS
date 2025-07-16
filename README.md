# Mental Health in Tech – R Markdown Analysis

This project analyzes survey data on mental health in the tech industry using R and R Markdown. The dataset spans multiple years (2017–2023) and is used to identify patterns, attitudes, and predictors related to mental health support and openness in workplaces.

## Project Structure
.
mental-health-analysis/
├── mental_health_analysis.Rmd   # Main R Markdown file
├── output.pdf  # report
├── data/                        # Folder containing datasets
│   ├── 2017.csv
│   ├── 2018.csv
│   └── ...
├── final_cleaned_data           # Cleaned and Combined data after Data processing
├── README.md                    # This file

## Objectives

- Clean and combine multiple years of mental health survey data
- Analyze changes in workplace mental health policies
- Build predictive models for willingness to disclose mental health issues
- Visualize key trends by year, gender, country, and support availability

## Key Technologies

- R: Data manipulation, cleaning, and modeling
- R Markdown: Reproducible reporting
- Tidyverse: Data wrangling (dplyr, ggplot2, etc.)
- Caret: Machine learning and evaluation

## Data Sources

- Source: OSMI Mental Health in Tech Surveys (https://www.kaggle.com/osmihelp/datasets)
- Years: 2017 to 2023

## How to Run

To run the analysis:

1. Clone this repo
2. Open `mental_health_analysis.Rmd` in RStudio
3. Click **Knit** to generate the HTML report

Make sure you have the required libraries installed. You can run:

```r
install.packages(c("tidyverse", "ggplot2", "caret", "readr"))
