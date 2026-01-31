# Loan Default Analysis – Power BI Project

## Project Overview

This is an **end-to-end educational Power BI project** focused on **DAX-heavy analytics**, data modeling, and validation.

The main goal of the project was **not just visualization**, but to deeply practice and apply:

* Advanced **DAX measures & calculated columns**
* **Dataflows** in Power BI Service
* Measure **validation & consistency checks**
* Time intelligence (YOY, YTD)
* Business-oriented financial insights

The project simulates a **loan default analysis** scenario across multiple dimensions such as employment type, age group, credit score, income bracket, and marital status.

---

## Data Source

* Educational dataset (used for learning & practice)
* Data ingested and prepared using **Power BI Dataflows**
* Cleaned, profiled, and transformed using **Power Query**

---

## Key Skills & Tools Used

* **Power BI Desktop & Power BI Service**
* **Power BI Dataflows**
* **Power Query (ETL & data profiling)**
* **DAX (Measures & Calculated Columns)**
* **Data validation techniques**

---

## DAX Concepts Applied

The project includes extensive use of DAX for both **measures** and **calculated columns**, including:

* `CALCULATE`
* `FILTER`
* `SUMX`, `AVERAGEX`, `MEDIANX`
* `COUNTROWS`
* `DIVIDE`
* `ALL`, `ALLEXCEPT`
* `VALUES`
* `SWITCH`

### Examples of DAX Use Cases

* Default Rate (%) calculations by Year and Employment Type
* Average & Median Loan Amount by Credit Score
* YOY Loan Amount Change
* YOY Default Loan Change
* YTD Loan Amount by Credit Score & Marital Status
* Dynamic calculations across Age Groups

Each major measure was **validated** by:

* Cross-checking totals
* Comparing against base aggregations
* Ensuring filter context behaves as expected

---

## Dashboards & Pages

### 1. Loan Default & Overview

* Default Rate (%) by Year
* Average Income by Employment Type
* Total Loan Amount by Loan Purpose
* Default Rate (%) by Employment Type
* Average Loan Amount by Age Group

### 2. Applicant Demographics & Financial Profile

* Total Loan by Credit Score (Age-based segmentation)
* Median Loan Amount by Credit Score
* Average Loan by Age Group & Marital Status
* KPI cards (Avg Income, Total Loan, Number of Loans)

### 3. Financial Risk Matrix

* YOY Loan Amount Change
* YOY Default Loan Change
* YTD Loan Amount by Credit Score & Marital Status
* Decomposition Tree (Income Bracket → Employment Type)

---

## Data Validation

Special focus was given to **data validation**, including:

* Validating calculated measures against raw aggregations
* Ensuring time intelligence measures return correct trends
* Cross-validation between visuals

This was done intentionally to ensure **DAX accuracy**, not just visual correctness.

---

## Notes

* This is a **learning-focused project**, built to strengthen real-world DAX and analytical thinking.
* Emphasis was placed on **logic, validation, and model behavior**, not only UI design.

---

## Project Access

* Interactive dashboard available via **Power BI Service**  
* Full PBIX file includes:

  * Data model
  * DAX measures
  * Power Query steps
  * Dataflow connection

---

## Author

**Abdallah**
Aspiring Data Analyst | Power BI & DAX Focused

---

If you have feedback, suggestions, or would like to discuss DAX logic used in this project, feel free to reach out.
