# **Ontario COVID-19 Test Positivity Visualization**

_Analyzing COVID-19 test positivity rates across various age groups in Ontario from May 1, 2020, to March 28, 2024._

---

## **Table of Contents**
1. [Introduction](#introduction)
2. [Motivation](#motivation)
3. [Dataset Description](#dataset-description)
4. [Visualizations](#visualizations)
5. [Quantitative Analysis](#quantitative-analysis)
6. [Technologies Used](#technologies-used)
7. [Setup and Usage](#setup-and-usage)
8. [Conclusion](#conclusion)
9. [Future Work](#future-work)

---

## **Introduction**
This project examines the trends in COVID-19 test positivity rates across various age groups in Ontario. By leveraging data visualization techniques, the goal is to identify how positivity rates varied over time and among different demographics.

### **Objective**
To answer the question:  
**"How did the COVID-19 test positivity rate vary among different age groups over time in Ontario?"**

---

## **Motivation**
Understanding the dynamics of the COVID-19 pandemic is crucial for public health responses. This project was inspired by narratives suggesting that older populations were most affected. Our analysis challenges these assumptions by diving deeper into the data to uncover insights.

---

## **Dataset Description**
The dataset, sourced from Ontario's public health data, includes:
- **Date:** The time range of the data spans from May 1, 2020, to March 28, 2024.
- **Age Groups:** Data segmented into 5 categories: `0to13`, `14to17`, `18to24`, `25to64`, and `65+`.
- **Positivity Rates:** 7-day rolling averages of test positivity percentages.

---

## **Visualizations**
This project utilizes the following visualizations to provide insights:
1. **Line Plot**: Trends in positivity rates over time for each age group.
2. **Heatmap**: Temporal patterns in positivity rates by age group.
3. **Box Plot**: Distribution of positivity rates across age groups.
4. **Bar Chart**: Average positivity rate by age group.
5. **Strip Chart**: Individual positivity rate data points by age group.

**Example Visualization:**  
![Visualization Example](ezgif.com-video-to-gif-converter (1).gif)

---

## **Quantitative Analysis**
Statistical measures were used to support visual findings:
- **Mean Positivity Rate:** Identifies the central tendency.
- **Median Positivity Rate:** Provides insights into typical values while reducing the influence of outliers.
- **Standard Deviation:** Measures the variability of positivity rates within each group.

### **Key Findings**
- The **18 to 24 age group** consistently exhibited higher positivity rates, peaking significantly in 2022.
- Temporal patterns revealed periods of high transmission, particularly in early 2022.

---

## **Technologies Used**
- **Python Libraries:**
  - `pandas`: Data manipulation.
  - `matplotlib` and `seaborn`: Visualizations.
  - `numpy`: Numerical analysis.
  - `plotly`: Interactive visualizations.

---

## **Setup and Usage**
### **Prerequisites**
Ensure the following libraries are installed:
```bash
pip install pandas matplotlib numpy seaborn plotly
