# Antimicrobial Stewardship & Antibiotic Utilization Analysis

### An Interactive Excel Dashboard for Antibiotic Utilization Monitoring

**Project Category:** Healthcare Analytics | Pharmacy Analytics | Data Analysis

**Tools:** Microsoft Excel, Power Query, Power Pivot, DAX, PivotTables and PivotCharts.

**Dataset:** 10,000+ Synthetic Antibiotic Dispensing Records

**Analysis Period:** January – August

---

## 1. Project Overview

Antibiotic utilization monitoring is an important aspect of pharmacy operations and antimicrobial stewardship.

Understanding which antibiotics are frequently dispensed, how utilization changes over time and how antibiotics are distributed across classification groups can provide useful information for further review.

This project explores antibiotic utilization through an interactive Excel dashboard developed using Power Query, Power Pivot, DAX and PivotTables.

The analysis focuses on unique patients, antibiotic quantities dispensed, frequently utilized antibiotics, monthly utilization patterns and WHO AWaRe classification distribution.

The project was inspired by my exposure to pharmacy operations and antimicrobial stewardship activities. The portfolio analysis, however, was independently recreated using synthetic data. No actual hospital patient records or confidential workplace transactions were used.

## 2. Business Problem

Pharmacy and healthcare teams need visibility into antibiotic utilization to understand consumption patterns and identify antibiotics that account for a significant proportion of dispensing activity.

Without an organized analytical view, monitoring frequently utilized antibiotics, comparing monthly activity and reviewing antibiotic classification distributions can become difficult.

The objective of this project was to develop an interactive Excel dashboard that organizes antibiotic dispensing information into meaningful indicators for utilization monitoring and further investigation.

## 3. Project Objectives

The project was designed to:

- Identify frequently utilized antibiotics based on unique patient counts.
- Calculate the number of unique patients receiving antibiotics.
- Examine total antibiotic quantities dispensed.
- Monitor monthly antibiotic utilization patterns.
- Analyse antibiotic distribution using the classification labels in the dataset.
- Present the findings through an interactive Excel dashboard.

## 4. Dataset Overview

The project uses a synthetic dataset containing more than 10,000 antibiotic dispensing records covering January to August.

The dataset contains information required to demonstrate antibiotic utilization analysis, including patient identifiers, antibiotic names, dispensing quantities, transaction details and dates.

The dataset was created for portfolio demonstration purposes and does not contain actual hospital patient records or confidential pharmacy transactions.

## 5. Tools and Technologies

**Microsoft Excel:** Used as the main analytical and dashboard development environment.

**Power Query:** Used for data cleaning, transformation, standardization and preparation.

**Power Pivot:** Used to work with the prepared data and create analytical calculations.

**DAX:** Used to create measures for calculating unique patients, total antibiotic quantities dispensed and other analytical comparisons.

**PivotTables and PivotCharts:** Used to summarize the data, examine utilization patterns and develop dashboard visualizations.

## 6. Data Cleaning and Transformation

Data preparation was carried out using Power Query.

The cleaning and transformation process included:

- Selecting relevant columns for the analysis.
- Removing unnecessary fields and irrelevant information.
- Handling blank values and removing duplicates.
- Correcting data types and standardizing column names.
- Excluding stock adjustment records because they represent inventory movements rather than patient dispensing activity.
- Retaining patient identifiers to support distinct patient calculations.
- Creating additional date attributes, including day, month, month number, quarter and year.
- Assigning AWaRe classification labels to the antibiotics using their identifiers.

After the transformation process, the prepared data was used for further analysis in Power Pivot.

## 7. Data Analysis

Power Pivot and DAX were used to create calculations for the dashboard.

The analysis included:

- Distinct counting of patient identifiers.
- Summation of antibiotic dispensing quantities.
- Identification of distinct antibiotics.
- Comparison of antibiotic utilization.
- Monthly utilization analysis.
- Previous-month comparisons and utilization trends.
- Analysis of antibiotic distribution across the classification labels.

PivotTables and PivotCharts were then used to present the results.

## 8. Key Performance Indicators

The dashboard includes the following indicators:

**Total Unique Patients:** Measures the number of distinct patients represented in the dataset.

**Total Antibiotic Quantity Dispensed:** Calculates the total quantity recorded as dispensed.

**Unique Antibiotics:** Shows the number of distinct antibiotics included in the analysis.

**Top Antibiotics:** Highlights antibiotics with the highest unique patient counts.

**Monthly Utilization:** Tracks changes in antibiotic utilization across the analysis period.

**Classification Distribution:** Shows the distribution of antibiotics across the classification labels used in the dataset.

## 9. Key Findings

The analysis produced the following findings:

- **6,002 unique patients** were identified across the eight-month analysis period.
- Approximately **42,000** in antibiotic dispensing quantity was recorded.
- The dataset contained **10 unique antibiotics**.
- Azithromycin IV 500mg recorded the highest unique patient count, with **971 patients**.
- May recorded the highest monthly utilization, with **1,220 unique patients**.

The five antibiotics highlighted in the top-utilization analysis were:

- Azithromycin IV 500mg – 971 patients.
- Ciprofloxacin IV – 969 patients.
- Ciprofloxacin IV Infusion 200mg – 969 patients.
- Gentamicin Injection 80mg – 953 patients.
- Meropenem Injection 1g – 948 patients.

The classification distribution showed:

- Watch – 51%.
- Access – 39%.
- Not Recommended – 10%.

These findings provide a descriptive overview of antibiotic utilization within the synthetic dataset.

## 10. Dashboard Features

The interactive Excel dashboard brings together the main utilization indicators and visualizations.

Its features include:

- KPI cards for key utilization metrics.
- Top five antibiotics by unique patient count.
- Monthly antibiotic utilization trends.
- Classification distribution.
- Patient and dispensing quantity comparisons.
- KPI trend indicators.
- Interactive date-based filtering.

The dashboard provides a consolidated view of the analysis and allows users to explore utilization patterns across the selected period.

## 11. Recommendations

Based on the descriptive findings, the following areas could be considered for further review:

- Reviewing frequently utilized antibiotics in the context of clinical indications and applicable treatment guidelines.
- Monitoring monthly changes in antibiotic consumption.
- Reviewing the utilization of Watch antibiotics as part of antimicrobial stewardship activities.
- Examining prescribing indications, dosage and treatment duration in future analyses.
- Incorporating culture and sensitivity results where available.
- Using pharmacy utilization reports to support more informed monitoring and review.

These recommendations require clinical interpretation and should not be treated as conclusions about prescribing appropriateness.

## 12. Project Limitations

This project uses synthetic data created for portfolio demonstration purposes.

The analysis measures antibiotic utilization but does not establish whether antibiotic prescribing was clinically appropriate.

The dataset does not include sufficient clinical information to assess:

- Treatment indications.
- Dosage appropriateness.
- Treatment duration.
- Patient treatment outcomes.
- Antimicrobial resistance.

The classification distribution is descriptive and should not be interpreted as evidence of inappropriate antibiotic prescribing.

The classification labels displayed in the analysis include Access, Watch and Not Recommended. Reserve is not represented in the displayed distribution.

## 13. Project Structure

The repository is organized into folders containing the project workbook and supporting materials.

- **Dashboard:** Contains the completed Excel dashboard workbook.
- **Screenshots:** Contains visual evidence of the dashboard and analytical workflow.
- **Report:** Contains the written project report.
- **DAX:** Contains the DAX measures used in the analysis.
- **Data:** Contains documentation about the synthetic dataset.

## 14. Key Learning Outcomes

Through this project, I developed practical experience in:

- Cleaning and transforming pharmacy-related data using Power Query.
- Working with Power Pivot for analytical calculations.
- Writing DAX measures in Excel.
- Using distinct patient counts to examine antibiotic utilization.
- Developing PivotTables and interactive Excel dashboards.
- Analysing monthly utilization patterns.
- Exploring antibiotic classification through the AWaRe framework.
- Communicating healthcare data findings through visualizations.

## 15. About the Author

I am a Pharmacy Technician developing my skills in healthcare analytics, data analysis and business intelligence.

My interest lies in applying analytical tools to pharmacy operations, medication utilization monitoring, inventory management and healthcare decision support.

This project reflects my interest in combining pharmacy knowledge with data analytics to explore practical healthcare challenges.
