# SQL Hotel Booking Cancellation Analysis – Identifying Reservation Cancellation Patterns Using SQL & Python

Analyzing hotel booking data to identify reservation cancellation patterns, customer behavior, pricing trends, booking channels, and hotel performance using SQL, Python, Jupyter Notebook, and professional business reporting.

**SQL Hotel Booking Cancellation Analysis Project**

---

## Live Report

**Executive Report:**

https://zainbaloach.github.io/Hotel-Booking-Cancellation-Analysis-Identifying-Reservation-Cancellation-Patterns-SQL-Python/

---

## Project Files

**Report (PDF):** Report.pdf

**Interactive HTML Report:** Report.html

**Jupyter Notebook:** Hotel_Booking_Cancellation_Analysis.ipynb

---

## 📑 Table of Contents

- [Overview](#overview---sql-hotel-booking-cancellation-analysis)
- [Business Problem](#business-problem)
- [Dataset](#dataset)
- [Tools & Technologies](#tools--technologies)
- [Project Structure](#project-structure)
- [Data Cleaning & Preparation](#data-cleaning--preparation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Research Questions](#research-questions)
- [Key Findings](#key-findings)
- [Project Deliverables](#project-deliverables)
- [How to Run This Project](#how-to-run-this-project)
- [Final Recommendations](#final-recommendations)
- [Author & Contact](#author--contact)

---

## Overview - SQL Hotel Booking Cancellation Analysis

This project presents an end-to-end hotel booking cancellation analysis designed to uncover the key factors influencing reservation cancellations across different hotel types, customer segments, booking channels, pricing strategies, and seasonal trends.

Using SQL for data exploration and business analysis, Python for data visualization, and Jupyter Notebook for analytical workflows, the project transforms raw hotel booking records into actionable business insights. The findings are presented through professionally designed reports in both PDF and interactive HTML formats, providing stakeholders with a clear understanding of cancellation behavior and opportunities to improve occupancy and revenue management.

---

## Business Problem

Hotel booking cancellations create significant operational and financial challenges for the hospitality industry. High cancellation rates reduce occupancy, impact revenue forecasting, complicate staffing decisions, and affect overall operational efficiency.

This project aims to:

- Identify the primary factors contributing to booking cancellations.
- Compare cancellation behavior across different hotel types.
- Analyze seasonal booking and pricing trends.
- Evaluate customer booking channels and market segments.
- Investigate country-wise cancellation behavior.
- Examine the relationship between pricing and reservation cancellations.
- Generate actionable business recommendations to improve occupancy and revenue performance.

---

## Dataset

The analysis is based on a hotel booking dataset containing reservation information across multiple customer segments, hotel types, booking channels, and countries.

### Key Dataset Dimensions Include

- Hotel Type
- Reservation Status
- Average Daily Rate (ADR)
- Arrival Date
- Market Segment
- Country
- Booking Channel
- Customer Type
- Reservation Cancellation Status

### Dataset Highlights

- Successful Reservations: **74,745**
- Cancelled Reservations: **44,152**
- Hotel Types: **City Hotel & Resort Hotel**
- Multiple International Customer Markets
- Seasonal Booking Data
- Pricing (ADR) Information

---

## Tools & Technologies

- SQL
- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Data Analysis
- Data Visualization
- Business Reporting
- HTML Reporting
- GitHub

---

## Project Structure

```text
SQL-Hotel-Bookings-Cancellation-Analysis/
│
├── README.md
│
├── README/
│   └── README.md
│
├── Data/
│   └── hotel_bookings2.csv
│
├── Notebook/
│   └── Hotel_Booking_Cancellation_Analysis.ipynb
│
└── Report/
    ├── Report.pdf
    └── Report.html
```

---

## Data Cleaning & Preparation

- Imported and explored the hotel booking dataset using SQL and Python.
- Validated reservation records and booking status information.
- Organized hotel, customer, market segment, and country attributes for analysis.
- Examined Average Daily Rate (ADR) values to support pricing analysis.
- Prepared monthly booking data for seasonal trend evaluation.
- Generated analytical datasets for SQL querying and Python visualizations.
- Created publication-ready charts for inclusion in the final PDF and HTML reports.

---

## Exploratory Data Analysis (EDA)

The analysis focused on:

- Reservation status distribution
- Hotel type cancellation comparison
- Average Daily Rate (ADR) analysis
- Monthly reservation trends
- Monthly ADR trends
- Country-wise cancellation analysis
- Market segment performance
- Market segment cancellation behavior
- ADR versus cancellation relationship
- Business recommendation development based on analytical findings

---

## Research Questions

- What is the overall reservation cancellation rate?
- How do cancellation rates differ between City Hotels and Resort Hotels?
- How does the Average Daily Rate (ADR) vary across hotel types?
- Which months record the highest booking activity and cancellation volume?
- How does ADR fluctuate throughout the year?
- Which countries contribute the highest number of cancelled reservations?
- Which market segments generate the highest booking and cancellation volumes?
- Is there a relationship between room pricing (ADR) and reservation cancellations?
- What business strategies can help reduce cancellation rates and improve revenue performance?

---

## Key Findings

- The dataset contains **74,745 successful reservations** and **44,152 cancelled reservations**, indicating that booking cancellations remain a significant operational challenge.
- **City Hotels** experienced a substantially higher cancellation rate (**approximately 41%**) compared to **Resort Hotels** (**approximately 27%**).
- **Resort Hotels** generally maintained higher **Average Daily Rate (ADR)** values, demonstrating stronger pricing power and greater revenue potential.
- **August** recorded the highest number of successful reservations, while **January** experienced the highest cancellation volume, highlighting clear seasonal booking behavior.
- ADR reached its highest levels during **January** and **July**, whereas **September** recorded the lowest average room prices.
- Approximately **70%** of all cancelled reservations originated from **Portugal (PRT)**, indicating a strong geographic concentration of cancellation risk.
- **Online Travel Agencies (Online TA)** generated the largest share of bookings (**approximately 47%**) and also contributed the highest proportion of cancellations (**approximately 46%**), demonstrating a significant dependence on third-party booking platforms.
- Reservations with **higher ADR values** were generally more likely to be cancelled, suggesting that higher-priced bookings carry greater financial risk.

---

## Project Deliverables

This repository includes the complete project resources developed throughout the analysis:

- SQL-based business analysis queries
- Jupyter Notebook containing the complete analytical workflow
- Python visualizations created using Matplotlib
- Professional business report in PDF format
- Interactive HTML version of the analytical report
- Clean and well-structured project documentation

---

## How to Run This Project

### Clone the Repository

```bash
git clone https://github.com/zainbaloach/SQL-Hotel-Bookings-Cancellation-Analysis.git
```

### Open the Jupyter Notebook

```text
Notebook/Hotel_Booking_Cancellation_Analysis.ipynb
```

### Review the Analytical Reports

```text
Report/Report.pdf
Report/Report.html
```

### Dataset Location

```text
Data/hotel_bookings2.csv
```

The notebook contains the complete SQL-based analysis, Python visualizations, and business insights used to produce the final reports.

---

## Final Recommendations

- Implement targeted cancellation reduction strategies for **City Hotels**, where cancellation rates are substantially higher.
- Investigate the unusually high cancellation volume originating from **Portugal** to better understand customer behavior and market-specific challenges.
- Strengthen **direct booking channels** to reduce reliance on third-party booking platforms, particularly Online Travel Agencies.
- Review cancellation policies associated with **Online Travel Agencies** and **Group bookings** to minimize avoidable reservation losses.
- Closely monitor **high-ADR reservations**, as these bookings demonstrate a greater likelihood of cancellation and represent a higher financial risk.
- Utilize seasonal booking and pricing trends to improve occupancy forecasting, optimize pricing strategies, and enhance revenue management throughout the year.

---

## Author & Contact

**Zain-Ul-Abideen**  
Data Analyst

📧 **Email:** zainbaloach007@gmail.com

🔗 **LinkedIn:** https://www.linkedin.com/in/zainb1/

🔗 **GitHub:** https://github.com/zainbaloach