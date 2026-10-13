Retail Sales Analytics & Statistical Validation

This repository contains all tasks completed as part of the 60-Day Data Analytics Internship at ApexPlanet Software Pvt. Ltd.

The project takes a raw online-retail dataset (Dec 2010 – Dec 2011) through four stages: cleaning, exploratory analysis, an interactive Power BI dashboard, and statistical validation of the findings.

Dashboard Preview

![Uploading dashboard.png…]()


Project Summary
Metric	Value
Total Revenue	£9.73M
Total Customers	4,372
Total Orders	25,900
Average Order Value	£375.52
Peak Month	November 2011 (£1.46M)
Tasks
Task 1: Data Cleaning & Preparation

Notebook: task 1.ipynb

Objective: Understand the raw retail dataset and prepare it for analysis.

Work done

Loaded and explored the dataset
Handled missing values and duplicates
Standardized data formats
Created a Revenue column (Quantity × UnitPrice)
Exported the cleaned dataset for further analysis

Output: Cleaned dataset ready for analysis

Task 2: Exploratory Data Analysis (EDA)

Notebook: task2.ipynb

Objective: Identify patterns, trends and key insights from the cleaned data.

Work done

Generated descriptive statistics
Created visualizations (line charts, bar charts, heatmaps)
Analyzed monthly revenue trends
Identified top-performing products
Performed cohort analysis for customer retention

Output: Insights about seasonality and customer behavior

Task 3: Interactive Dashboard (Power BI)

Notebook: task 3.ipynb · Dashboard: powerbi/SalesDashboard.pbix · PDF: powerbi/dashboard.pdf

Objective: Build an interactive dashboard that turns the analysis into a decision-support tool for business stakeholders.

Work done

Defined KPIs: Total Revenue, Total Customers, Total Orders, Average Order Value
Built a monthly revenue trend to monitor seasonality and peak demand
Built a top-10 products analysis to show revenue concentration
Added a cohort retention matrix for customer lifecycle and repeat-purchase behavior
Added Country and Month slicers for dynamic exploration of revenue, customers and products

Output: Interactive business dashboard

How to open: Download SalesDashboard.pbix and open it in Power BI Desktop. GitHub can't display Power BI files, so use the preview image above or the PDF export if you don't have Power BI.

Data notes

Revenue includes returns and cancelled invoices, so Total Orders includes cancellations.
December 2011 is a partial month, so the drop at the end of the trend is not a real decline.
Missing CustomerIDs were imputed during cleaning, so customer-level figures are approximate.
"POSTAGE" and "DOTCOM POSTAGE" are shipping fees, not products.
Task 4: Statistical Validation & Business Storytelling

Notebook: task 4.ipynb

Objective: Validate insights using statistical hypothesis testing.

Work done

Defined the business question
Formulated null and alternative hypotheses
Applied an Independent Two-Sample T-Test
Interpreted the p-value
Developed business recommendations

Result: The seasonal revenue increase is driven by higher transaction volume, not higher order value.

Repository Structure
├── task 1.ipynb                  # Data cleaning & preparation
├── task2.ipynb                   # Exploratory data analysis
├── task 3.ipynb                  # Dashboard data preparation
├── task 4.ipynb                  # Hypothesis testing
├── cleaned_dataset (1).xls       # Cleaned dataset
├── compressed_data.csv.gz        # Dashboard-ready dataset
├── data_dictionary.xls           # Column descriptions
├── powerbi/
│   ├── SalesDashboard.pbix       # Power BI dashboard
│   ├── dashboard.png             # Dashboard preview
│   └── dashboard.pdf             # PDF export
└── README.md
Tools Used
Python: Pandas, NumPy, Matplotlib, Seaborn, SciPy
Jupyter Notebook
Power BI
GitHub
Author

Vaibhavi Vaishnav Data Analytics Intern, ApexPlanet

GitHub: vaibhavi-vaishnav
LinkedIn: Vaibhavi Vaishnav
