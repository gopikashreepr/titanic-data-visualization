# Titanic Data Visualization Report
**Tools:** Power BI · DAX · Exploratory Data Analysis  
**Domain:** Data Visualization · Survival Analysis  
**Dataset:** Titanic Passenger Dataset (Kaggle)

---

## Business Problem
The Titanic disaster of 1912 remains one of history's most studied events in data science. This project uses visual analysis to answer a core question: **what factors determined survival?** By analyzing passenger class, gender, embarkation point, and demographics, we can understand the systemic and social factors that influenced who survived.

## Dataset
- Source: [Titanic Dataset — Kaggle](https://www.kaggle.com/c/titanic/data)
- Records: 891 passengers
- Key fields: Survived, Pclass (passenger class), Sex, Age, Fare, Embarked (port), SibSp, Parch

## Dashboard Overview
Single-page visual report with 4 KPI cards and 7 analytical visuals:

| Visual | Insight |
|---|---|
| Clustered Bar | **Survival by Passenger Class and Gender** — class + gender interaction |
| Funnel | **Passenger Count by Class** — class distribution of all passengers |
| Treemap | **Survival by Embarkation Port** — did port of boarding affect survival? |
| Donut | **Overall Survival Rate** — total survived vs perished |
| Donut | **Passenger Class breakdown by Gender** — demographic profile |
| Line chart | Survival trend analysis |
| Pivot table | Detailed passenger-level breakdown |

**Slicers:** Filter by class, gender, embarkation port, and survival status

**KPI Cards:** Total passengers, survival count, survival rate %, average fare

## Key Business Questions Answered
1. Did passenger class significantly affect survival probability?
2. Were women and children more likely to survive than men?
3. Did embarkation port (Southampton, Cherbourg, Queenstown) influence survival outcomes?
4. What was the overall survival rate, and how does it break down by demographic?

## Key Insights
- First class passengers had a significantly higher survival rate than second and third class, reflecting both proximity to lifeboats and evacuation priority
- Gender was the strongest single predictor of survival — "women and children first" protocol is clearly visible in the data
- Embarkation port shows a survival rate variance, potentially reflecting the demographic makeup of passengers boarding at each port
- The combination of class + gender creates a clear survival hierarchy visible in the clustered bar breakdown

## Tools & Techniques
- Power BI Desktop — single-page visual report
- DAX — survival rate %, count measures
- Treemap, funnel, donut, bar, and pivot table visuals
- Interactive slicers for multi-dimensional filtering

## How to Run
1. Download `TITANIC_DATA_VISUALIZATION_REPORT_.pbix`
2. Open in Power BI Desktop
3. Use the 4 slicers to filter by class, gender, port, and survival status

---
*Project by Gopikashree PR | [LinkedIn](https://www.linkedin.com/in/gopikashree-pr/) | [GitHub](https://github.com/gopikashreepr)*
