# 🚇 TTC Subway Delay Data Analysis – DSI_ML_Team8

We’re exploring five years of Toronto’s TTC subway delay logs to uncover patterns, build predictive models, and offer real-world recommendations—helping prevent future delays and inform commuters earlier for better trip planning.

📁 [Dataset Source (Open Data Toronto)](https://open.toronto.ca/dataset/ttc-subway-delay-data/)

---

## Table of Contents

- [Overview](#overview)
- [Learning Outcomes](#learning-outcomes)
- [Project Overview](#project-overview)
- [Tools & Libraries](#tools--libraries)
- [Getting Started](#getting-started)
- [Schedule and Project Plan](#schedule-and-project-plan)
- [Team Members](#team-members)
- [Folder Structure](#folder-structure)
- [Project Facilitators](#project-facilitators)
- [Other Resources](#other-resources)

---

## Overview

This project analyzes the TTC Subway Delay Data using time-based and operational features. Our focus is to uncover predictive signals around subway disruptions, evaluate delay classification models, and surface insights that could inform both TTC operations and trip planning for riders.


---

## Learning Outcomes

By the end of this sprint, we aim to:

1. Apply technical skills across EDA, regression, time series modeling, and Git collaboration  
2. Build a portfolio-ready, reproducible data science project  
3. Work collaboratively using GitHub, Notion, and Slack  
4. Communicate results clearly through a README, visualizations, and a final presentation

---

## Project Overview

- **Dataset**: [TTC Subway Delay Data](https://open.toronto.ca/dataset/ttc-subway-delay-data/)
- **Publisher**: Toronto Transit Commission  
- **Last Refreshed**: June 30, 2025  
- **Contents**: Monthly delay logs across subway lines, including time, location, duration, and delay cause  
- **Objective**: Generate a reproducible machine learning pipeline for delay trend analysis and prediction

---

## Tools & Libraries

We expect to use:

- [`pandas`](https://pandas.pydata.org/) for data manipulation  
- [`numpy`](https://numpy.org/) for numerical operations  
- [`scikit-learn`](https://scikit-learn.org/) for modeling  
- [`matplotlib`](https://matplotlib.org/) and [`seaborn`](https://seaborn.pydata.org/) for visualization  
- [`Prophet`](https://facebook.github.io/prophet/) or [`statsmodels`](https://www.statsmodels.org/stable/index.html) for time series (TBD)  
- [`SHAP`](https://shap.readthedocs.io/en/latest/) for explainability (optional)  
- [GitHub](https://github.com/) for version control  
- [Slack](https://slack.com/) for async communication  
- [Trello](https://trello.com/invite/b/68784cb94b65902aba3eaf1b/ATTI02762885d9b118c31ccbfa7dacd1992b7739A217/🚇-our-1-week-ttc-delay-ml-mission) for documentation & Kanban  

Reflection videos will be linked in this README.

---

## Getting Started

This is a 10-day team sprint running from **July 17 to July 26, 2025**. All work will be documented in GitHub, with daily async check-ins on Slack and Notion.

---

## Schedule and Project Plan

| Date       | Phase                   | Key Goals                                                       | Owner(s)                                                                                                                                   |
|------------|-------------------------|------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| July 17    | Kickoff & Planning      | Finalize dataset, roles, create repo, folder structure, README               | Everyone, [@val-poon](https://github.com/val-poon)                                                                                   |
| July 18–19 | EDA & Feature Engineering | Complete EDA, preprocess, create time-based features             | [@Saadkhan-188](https://github.com/Saadkhan-188), [@smodi23](https://github.com/smodi23)                                                   |
| July 21    | Modeling                | Train & evaluate logistic regression baseline                    | [@reachsneha02](https://github.com/reachsneha02), [@suchi-dev-ai](https://github.com/suchi-dev-ai)                                        |
| July 22    | Visualizations & Recs  | Build charts, identify key trends, draft insights                | [@reachsneha02](https://github.com/reachsneha02), [@suchi-dev-ai](https://github.com/suchi-dev-ai)                                        |
| July 23    | README + Reporting     | Finalize README, visual assets, and insight write-up/ slide deck             | [@val-poon](https://github.com/val-poon)                                                                                            |
| July 24    | Slides + Reflection Videos | Record 3–5 min videos + upload             | Everyone                                                                                                                                   |
| July 25    | Final Touches          | Polish notebooks, test reproducibility, push final GitHub repo   | Everyone                                                                                                                                   |
| July 26    | Final Presentation     | Present findings to cohort                                       | Everyone                                                                                                                                   |



---

## Team Members

| Name                    | GitHub Handle     | Email                        | Contributions	               | Reflection Video |
|-------------------------|------------------|------------------------------|--------------------|------------------|
| Valerie Poon            | [@val-poon](https://github.com/val-poon)         | valerieyfp@gmail.com         | PM, Reporting      | _TBD_            |
| Saad Khan               | [@Saadkhan-188](https://github.com/Saadkhan-188)     | saadkhan188@gmail.com        | Data Cleaning, Feature Engineering, EDA	            | _TBD_            |
| Sahil Modi              | [@smodi23](https://github.com/smodi23)     | sahilmodi237@gmail.com       | Data Cleaning, Feature Engineering, EDA	            | _TBD_            |
| Sneha Gupta             | [@reachsneha02](https://github.com/reachsneha02)   | reachsneha02@gmail.com       | Modeling, Visualizations, Final Report	           | _TBD_            |
| Sucharitha Sundararaman| [@suchi-dev-ai](https://github.com/suchi-dev-ai)     | Suchiraman22@gmail.com       | Modeling, Visualizations, Final Report	           | _TBD_            |
| Faiz Shaikh             | _TBD_             | _TBD_                        | TBD (away)         | _TBD_            |

---

## Folder Structure

```
DSI_ML_Team8/
├── data/
│   ├── raw/         # Unmodified source data
│   ├── processed/   # Cleaned and engineered datasets
│   └── external/    # External reference files
├── notebooks/       # Jupyter notebooks for EDA and modeling
├── models/          # Serialized models and performance metrics
├── visuals/         # Charts and figures for reporting and slides
├── reports/         # Final presentations, summaries, and documentation
├── src/             # Python scripts and feature engineering tools
├── .gitignore
└── README.md
```


---

## Project Facilitators

| Role                 | Name              | Email                              |
|----------------------|-------------------|-------------------------------------|
| Tech Facilitator     | Phil Van-Lane     | phil.vanlane@mail.utoronto.ca      |
| Learning Support     | Aditya Kulkarni   | aditya.kulkarni@mail.utoronto.ca   |
| Learning Support     | Ernani Fantinatti | ernanif@fantinatti.com             |
| Learning Support     | Laura MacKew      | lauramackew@gmail.com              |

---

## Other Resources

- [Team Trello (Kanban & Docs)](https://trello.com/invite/b/68784cb94b65902aba3eaf1b/ATTI02762885d9b118c31ccbfa7dacd1992b7739A217/🚇-our-1-week-ttc-delay-ml-mission)
- [Slack Channel – DSI Certificate Program](https://uoft-dsi-certificates.slack.com/archives/C096UPGDKA4)

---

