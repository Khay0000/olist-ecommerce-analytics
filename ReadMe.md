

\# E-commerce Revenue and Customer Retention Analysis



An end-to-end analytics project using SQL, Python, Excel and Power BI to find where an online marketplace is losing revenue and customers, and what to fix first.



\*\*Status:\*\* In progress (Day 1: repo setup)



\## Business context

Leadership at an online marketplace sees sales growing, but most customers buy once and never return, and some orders arrive late. This project investigates where the business is losing money and recommends what to fix first.



\## Business questions

1\. How have revenue and order volume changed over time, and which product categories and regions drive them?

2\. What share of customers buy again, and how does retention differ across cohorts?

3\. Do late deliveries lead to bad reviews, and do bad reviews lead to fewer repeat purchases?

4\. Which customer segments are the most valuable, and which are at risk of leaving?



\## Dataset

Brazilian E-Commerce Public Dataset by Olist (Kaggle): about 100,000 orders from 2016 to 2018, split across relational tables (orders, items, customers, products, sellers, payments, reviews).



The raw files are not stored in this repo. Download the dataset from Kaggle and place the CSV files in `data/raw/`.



\## Tools and their roles

\- \*\*Excel:\*\* data profiling, pivot tables and a one-page KPI summary

\- \*\*SQL (MySQL):\*\* joins and aggregations for revenue, retention, cohorts and delivery delays

\- \*\*Python:\*\* customer segmentation (RFM) and the delivery vs review analysis

\- \*\*Power BI:\*\* executive dashboard



\## Project structure

\- `data/raw/`: original CSV files (not tracked)

\- `data/processed/`: cleaned and exported data

\- `sql/`: queries, one file per business question

\- `notebooks/`: Python analysis

\- `excel/`: pivot-table workbook and KPI summary

\- `dashboard/`: Power BI file

\- `images/`: screenshots and the table-relationship diagram

\- `docs/`: final write-up and decision log



\## Progress log

\- Day 1: repository created



\## Methodology

TODO: describe how you loaded the data, how you defined key terms (for example "repeat customer"), and what you cleaned or excluded.



\## Key findings

TODO: add findings backed by numbers from your analysis.



\## Recommendations

TODO: add 3 to 5 specific recommendations.



\## Dashboard

TODO: add a screenshot once the dashboard is built.



\## Limitations

\- The data covers only 2016 to 2018.

\- Review scores are self-selected, so they may not represent all customers.

\- Delivery delays may have causes that the data does not show, so the analysis can show association, not proof of cause.



\## How to run

TODO: add setup steps once the project is built. Database credentials are never stored in this repo.

EOF

