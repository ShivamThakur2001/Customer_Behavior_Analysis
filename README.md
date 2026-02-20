📊 Data Analytics Project – End-to-End Business Insights
📌 Overview

This project demonstrates a complete end-to-end data analytics workflow, starting from raw dataset processing to interactive dashboard visualization.

The objective of this project is to:

Load and preprocess data using Python

Perform Exploratory Data Analysis (EDA)

Clean and transform data

Store and query data using PostgreSQL

Build an interactive dashboard in Power BI

Generate actionable business insights

This project reflects real-world data analytics practices used in industry.

📂 Dataset

The dataset contains customer transaction and purchase information, including:

Customer ID

Age

Gender

Product Category

Purchase Amount

Review Rating

Payment Method

Shipping Type

Subscription Status

Purchase Frequency

The data was cleaned and structured for analysis and reporting.

🛠 Tools & Technologies Used

Python (Data processing & EDA)

Pandas & NumPy (Data manipulation)

Matplotlib / Seaborn (Visualization)

PostgreSQL (Database management)

SQL (Data querying & aggregation)

Power BI (Interactive dashboard & reporting)

🔎 Project Steps
1️⃣ Data Loading

Imported dataset into Python using Pandas

Checked structure, data types, and missing values

2️⃣ Exploratory Data Analysis (EDA)

Summary statistics

Distribution analysis

Category-wise comparisons

Correlation analysis

3️⃣ Data Cleaning

Handled missing values

Fixed inconsistent data formats

Created derived columns (e.g., Age Groups, Purchase Frequency in Days)

Removed duplicates and invalid entries

4️⃣ Database Integration

Connected Python to PostgreSQL

Loaded cleaned dataset into database tables

Performed SQL queries for:

Aggregations

Filtering

Grouping

Business metrics calculation

5️⃣ Dashboard Development

Connected Power BI to PostgreSQL

Built interactive visualizations

Designed KPI cards and charts

Added slicers and filters for dynamic analysis

📊 Dashboard

The Power BI dashboard includes:

Total Customers

Total Revenue

Average Review Rating

Category-wise Sales

Purchase Frequency Analysis

Subscription Impact Analysis

Seasonal Sales Trends

The dashboard enables business stakeholders to quickly understand performance trends and customer behavior.

📈 Results & Insights

Key insights derived from the analysis:

Identified top-performing product categories

Analyzed customer purchasing patterns

Determined impact of subscription status on revenue

Found seasonal trends in purchasing behavior

Evaluated customer review ratings across categories

The project demonstrates how raw data can be transformed into actionable business insights.

▶️ How to Run the Project
Step 1: Clone the Repository
git clone <repository-link>
cd project-folder
Step 2: Install Required Libraries
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2
Step 3: Run Data Processing Script
python main.py
Step 4: Load Data into PostgreSQL

Ensure PostgreSQL is running and update database credentials in the script.

Step 5: Open Power BI

Connect to PostgreSQL database

Load required tables

Open the provided .pbix dashboard file

👤 Author
Shivam Thakur
Data Analytics Enthusiast
