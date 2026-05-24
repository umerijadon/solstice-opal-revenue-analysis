# solstice-opal-revenue-analysis

## Project Overview
This project analyzes ancillary revenue performance for **Solstice Opal Hotel**, a luxury hospitality business seeking to understand which guest segments generate the highest additional revenue through services such as spa, dining, and hotel activities.

The objective of the analysis was to:
- Identify the guest segments driving ancillary revenue
- Understand behavioral and booking patterns linked to higher spending
- Develop KPI frameworks for leadership monitoring
- Provide actionable recommendations to maximize ancillary revenue opportunities

The analysis was conducted using Python with a focus on:
- Data cleaning and validation
- Exploratory Data Analysis (EDA)
- Customer segmentation
- KPI development
- Executive-focused reporting and visualization

---

# Business Problem
Leadership observed significant differences in ancillary spending across guests but lacked visibility into:
- Which customer segments contribute the most revenue
- Which booking channels drive high-value guests
- Which guest types underutilize ancillary services
- Opportunities to improve ancillary conversion rates

The project aimed to transform fragmented operational data into actionable business insights.

---

# Datasets Used

## Guest Profiles
Contains:
- Guest ID
- Loyalty Tier
- Marketing Consent Status

## Stay Details
Contains:
- Stay ID
- Booking Channel
- Check-in Date
- Reason for Stay
- Number of Guests

## Ancillary Spend
Contains:
- Guest ID
- Ancillary Category
- Amount Spent

---

# Data Validation & Cleaning
The datasets originated from multiple operational systems and required extensive cleaning before analysis.

Key cleaning steps included:
- Standardizing column names and categorical values
- Handling missing values
- Converting invalid numeric fields
- Removing duplicate records
- Validating guest identifiers
- Correcting inconsistent text formatting
- Filtering invalid spending transactions

The workflow ensured analytical consistency across all merged datasets.

---

# Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# Key KPIs Developed

The following business KPIs were created:

- Total Ancillary Revenue
- Average Ancillary Revenue per Stay
- Ancillary Conversion Rate
- Average Spend per Guest
- Average Transaction Value

Primary KPI Recommendation:
> **Average Ancillary Revenue per Stay**

This metric directly measures how effectively each stay generates additional revenue.

---

# Exploratory Analysis Performed

The analysis explored:
- Revenue distribution patterns
- Booking channel performance
- Loyalty tier spending behavior
- Reason-for-stay comparisons
- Ancillary category performance
- Guest segmentation trends

---

# Key Insights

## Loyalty Tier Impact
Higher loyalty tiers generated significantly stronger ancillary revenue per stay compared to lower-tier guests.

## Booking Channel Performance
Certain booking channels consistently attracted higher-spending guests, indicating opportunities for targeted partnerships and promotions.

## Leisure vs Business Guests
Leisure travelers demonstrated stronger ancillary engagement compared to business travelers.

## Category Revenue Drivers
Specific ancillary categories contributed disproportionately to overall revenue performance.

## Revenue Optimization Opportunity
A large portion of guests showed low ancillary conversion despite high stay volume, representing potential upselling opportunities.

---

# Visualizations Included

The project includes:
- Distribution of Ancillary Spend
- Booking Channel Analysis
- Revenue by Ancillary Category
- Revenue by Loyalty Tier
- Segment-Based Revenue Comparisons

---

# Recommendations

Based on the analysis, leadership should consider:

1. Increasing targeted offers toward high-spending loyalty segments
2. Promoting high-performing ancillary services during booking and check-in
3. Developing bundled offers for low-conversion guest groups
4. Monitoring ancillary revenue KPIs weekly
5. Using booking-channel insights to optimize marketing strategy

---

# Estimated Project Scale

- Analyzed thousands of hospitality transaction records
- Built 5+ analytical visualizations
- Developed executive-facing KPI reporting
- Automated multi-source data cleaning and aggregation workflows

---

# Project Deliverables

This repository contains:
- Cleaned analytical datasets
- Python analysis notebook
- Business visualizations
- Executive presentation
- Written analytical report
- KPI summary outputs

---

# Author

**Jadon Umeri**  
Aspiring Data Analyst focused on business analytics, customer insights, revenue optimization, and data-driven decision-making.
