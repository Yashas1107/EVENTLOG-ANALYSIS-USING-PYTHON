# Event Log Analysis Using Python

## Overview

This project analyzes system event logs using Python to identify failure patterns, peak issue timings, and operational insights.

Using data cleaning, transformation, and visualization techniques, the project helps understand when failures occur most frequently and how event trends change over time.

---

## Tools & Technologies

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Key Tasks Performed

* Cleaned and transformed raw event log data
* Converted timestamp columns into datetime format
* Filtered failure events
* Performed time-based analysis
* Created visualizations for failure trends
* Identified peak hours with maximum failures

---

## Sample Analysis

```python
# Extract hour from timestamp
df['Hour'] = df['Date and time'].dt.hour

# Filter failure events
failure_df = df[df['Event code'] == 'FAILURE']
```

---

## Insights

* Failure events occurred more frequently during specific hours
* Time-based analysis helped identify recurring patterns
* Data cleaning improved overall analysis accuracy

---

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* ETL Concepts
* Data Visualization
* Python Programming

---

