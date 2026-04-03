# CS105 Survey Analysis

## Overview

This project analyzes student survey data to explore factors affecting learning effectiveness in classroom environments. The analysis focuses on relationships between focus duration, phone usage, external distractions, and perceived learning outcomes.

---

## Dataset

* Survey responses collected from students
* Cleaned and filtered for relevant variables:

  * Learning effectiveness (1–5 scale)
  * Focus duration
  * Phone/social interaction frequency
  * External distractions

---

## Methods

### Data Processing

* Selected relevant survey columns
* Renamed variables for clarity
* Converted categorical responses into numerical scales
* Removed missing values

### Exploratory Data Analysis (EDA)

* Generated multiple visualizations (bar charts, distributions, etc.)
* Examined trends between behavioral factors and learning effectiveness

### Statistical Analysis

* **Chi-square test**
  Tested associations between categorical variables

* **Independent t-test**
  Compared learning effectiveness across different behavior groups

* **Correlation analysis**
  Evaluated relationships between numerical variables

---

## Key Insights
- No statistically significant relationship was found between phone usage or external distractions and learning effectiveness  
- Focus duration shows a positive relationship with perceived learning effectiveness based on visual analysis  
- Students who reported feeling more unprepared also tended to report lower learning effectiveness  
- Overall, results suggest that internal factors (such as focus and preparedness) may play a larger role than external distractions, though some relationships were inconclusive  


## Additional Observations
- While the primary analysis focused on external factors (phone usage and distractions), exploratory visualizations suggest that focus duration and perceived preparedness may be more closely related to learning effectiveness  
- These factors were not formally tested in the hypothesis framework and could be explored further in future analysis

---

## Tools & Technologies

* Python
* pandas, numpy
* matplotlib, seaborn
* scipy

---

## Repository Structure

```
cs105-survey-analysis/
│── cs105-survey-analysis.ipynb
│── survey_data.csv
│── README.md
```

---

## Notes

Developed as part of a group project; analysis and early visualization sections primarily authored by me, Kyle Russell.
