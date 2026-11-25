# Ilsan Hidayatuloh | Data Portfolio

**Informatics Engineering Student | Aspiring Data Analyst & Data Scientist**

Welcome to my data portfolio! This repository showcases my projects in Data Analysis, Business Intelligence, Data Science, and Machine Learning, with a focus on turning data into meaningful insights and practical business solutions.

---

## About Me

Hi, I'm Ilsan Hidayatuloh, an undergraduate Informatics Engineering student at Langlangbuana University, Indonesia.

My interest in data began with a curiosity about how businesses use information to understand problems, make decisions, and improve their performance. Through my academic journey, independent projects, and practical experience, I have been developing my skills in data processing, statistical analysis, visualization, and machine learning.

I primarily work with **Python, SQL, Microsoft Excel, Tableau, and Streamlit**. I enjoy exploring datasets, identifying patterns, building predictive models, and presenting findings through dashboards that are both informative and easy to understand.

I am continuously expanding my technical and analytical skills, particularly in applying data-driven approaches to real business challenges. I am also interested in internship and entry-level opportunities where I can contribute, collaborate, and continue learning from experienced professionals.

### Technical Skills

| Category | Tools & Technologies |
|---|---|
| Programming | Python, SQL |
| Data Analysis | Pandas, NumPy, Microsoft Excel |
| Data Visualization | Matplotlib, Seaborn, Plotly, Tableau |
| Machine Learning | Scikit-learn, Regression, Forecasting |
| Business Intelligence | Excel PivotTables, KPI Analysis, Tableau |
| Dashboard Development | Streamlit, Tableau Public |
| Development Tools | Git, GitHub, Jupyter Notebook, VS Code, Google Colab |
| Database | MySQL, PostgreSQL |

---

## Table of Contents

- [About Me](#about-me)
- [Portfolio Projects](#portfolio-projects)
- [Education](#education)
- [Experience](#experience)
- [Certificates](#certificates)
- [Contact](#contact)

---

# Portfolio Projects

This portfolio includes projects from different industries, including automotive, e-commerce, retail, and customer analytics.

Each project reflects a different part of my learning journey, from preparing and understanding data to developing analytical solutions and communicating business insights.

## 1. Data Science & Machine Learning

### 1.1 Astra Automotive Intelligence — Sales Analytics & Forecasting

**[Live Interactive Dashboard](https://astra-automotive-intelligence-ilsan.streamlit.app/)** | **[GitHub Repository](https://github.com/Ilsan08/astra-automotive-intelligence)**

**Project Overview**

Astra Automotive Intelligence is an end-to-end data science and business analytics project developed to examine Indonesia's automotive market performance and forecast monthly vehicle sales.

Using publicly available automotive wholesale data published through Astra International Investor Relations, with GAIKINDO as the underlying source, this project explores historical sales trends, market share movements, and the competitive landscape between Astra and non-Astra automotive groups.

The project was developed as an independent portfolio case study, combining data analysis, machine learning, and an interactive web application.

**Project Objectives**

- Analyze historical automotive wholesale sales and market share.
- Examine changes in Astra's market position relative to competitors.
- Identify sales patterns, trends, and seasonal fluctuations.
- Develop and compare forecasting approaches to estimate future sales volume.
- Present analytical findings through an interactive business dashboard.

**Methodology & Development**

The project follows a structured data science workflow, beginning with business understanding and data exploration. Two datasets were used: monthly market-level sales data and brand-level sales records.

During data preparation, I examined data quality, checked for missing values and duplicates, validated sales totals, and performed Exploratory Data Analysis (EDA) to better understand the automotive market.

Feature engineering was then applied to create lag variables, historical rolling averages, and calendar-based features for time-series forecasting.

Four forecasting approaches were evaluated:

1. Naive Forecasting
2. Seasonal Naive Forecasting
3. Moving Average
4. Ridge Regression

Rather than relying on a random train-test split, the project uses chronological data splitting and walk-forward evaluation to preserve the time-dependent nature of automotive sales.

Model performance is assessed using MAE, RMSE, WAPE, and R², with model selection based on validation performance.

**Interactive Dashboard**

To make the analysis more accessible, I developed a web-based dashboard using Streamlit and Plotly.

The application includes five interactive sections:

- **Executive Overview:** Automotive sales performance, market share, growth trends, and seasonal analysis.
- **Brand & Competition:** Brand rankings, market composition, and competitive sales comparisons.
- **Sales Forecasting:** Historical sales visualization, next-month forecasting, and what-if scenario simulations.
- **Model Performance:** Forecasting model comparison, actual-versus-predicted values, and residual analysis.
- **Data & Methodology:** Dataset information, data quality validation, and analytical methodology.

The dashboard brings together descriptive and predictive analytics in a format designed to support business interpretation and decision-making.

**Key Findings**

The analysis highlights the importance of evaluating sales volume alongside market share. An increase in a company's sales does not necessarily indicate stronger competitive positioning if the overall market grows faster.

The forecasting experiment also demonstrates why simpler statistical approaches should be evaluated alongside machine learning models, particularly when working with limited historical observations.

These findings provide a practical foundation for discussing market monitoring, demand planning, and business performance evaluation.

**Technology Stack:** Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly, Streamlit, Git & GitHub.

**Project Type:** Data Science, Predictive Analytics, Business Intelligence, Time Series Forecasting.

**Project Links**

- **Live Application:** [Astra Automotive Intelligence Dashboard](https://astra-automotive-intelligence-ilsan.streamlit.app/)
- **Source Code:** [GitHub — Astra Automotive Intelligence](https://github.com/Ilsan08/astra-automotive-intelligence)
- **Data Source:** [Astra International Investor Relations](https://www.astra.co.id/en/investor-relations/monthly-update)

*Disclaimer: This is an independent educational and portfolio project. It is not developed, sponsored, or officially affiliated with PT Astra International Tbk.*

---

### 1.2 E-Commerce Sales Analytics — Olist Dataset

**[View Project Notebook](./E-Commerce%20Sales%20Analytics%20Dashboard.ipynb)**

![E-Commerce Sales Analytics Dashboard](https://github.com/user-attachments/assets/7e7679df-49e1-419a-9abd-cee63a57fa4f)

**Project Overview**

This project focuses on analyzing e-commerce transactions using the Brazilian Olist dataset to better understand sales performance, customer purchasing behavior, payment preferences, and customer satisfaction.

The dataset contains nine interconnected relational tables, covering information such as orders, customers, products, payments, sellers, and reviews.

The project began with setting up the working environment in Google Colab and extracting the dataset files. Each table was examined to understand its structure, identify missing values, detect duplicate records, and check data types before further analysis.

**Data Preparation & Analysis**

During preprocessing, I converted relevant columns into datetime formats, handled missing information, and translated product category names from Portuguese into English to improve readability.

The relational datasets were then integrated for further analysis, with attention to the relationships between orders, customers, products, payments, and reviews.

Exploratory Data Analysis (EDA) was performed to investigate:

- Sales trends and order activity over time.
- Customer purchasing patterns.
- Popular product categories.
- Payment methods and installment preferences.
- Customer review scores and satisfaction patterns.

The analysis helps illustrate how different parts of an e-commerce business can be examined together to produce a broader understanding of operational and commercial performance.

**Project Outcome**

The project produced an integrated analytical dataset and a collection of visualizations highlighting key aspects of e-commerce activity.

It also provided practical experience in working with relational data, managing data quality, and translating transactional information into business-oriented analysis.

The resulting dataset can serve as a foundation for further dashboard development and more advanced customer or sales analytics.

**Technology Stack:** Python, Pandas, NumPy, Matplotlib, Seaborn, Google Colab.

**Project Type:** E-Commerce Analytics, Exploratory Data Analysis, Data Preparation, Business Analytics.

---

## 2. Python Data Analysis Projects

### 2.1 Mall Customer Segmentation Analysis

**[View Project Notebook](./Mall_Customers.ipynb)**

**Project Overview**

This project explores customer characteristics and spending behavior to identify patterns that may support more targeted marketing strategies.

Using customer information such as annual income and spending scores, I performed exploratory analysis to understand the differences in purchasing behavior across customer groups.

**Key Activities**

- Explored customer demographics and spending characteristics.
- Performed data inspection and preprocessing.
- Visualized relationships between annual income and spending scores.
- Examined customer groups with different spending behaviors.

**Key Insight**

The analysis highlighted differences between high-spending customers and customers with relatively high incomes but more conservative spending behavior. These patterns can provide useful starting points for customer targeting and marketing discussions.

**Technology Stack:** Python, Pandas, Matplotlib, Seaborn.

**Project Type:** Customer Analytics, Exploratory Data Analysis.

---

### 2.2 H&M Global Store Data Cleaning & Feature Engineering

**[View Project Notebook](./ALL_H&M_STORES_WORLDWIDE.ipynb)**

**Project Overview**

This project focuses on preparing a global H&M store dataset for reliable analysis and visualization.

The main objective was to improve data consistency and create a structured dataset that could support further analysis of H&M's international retail presence.

**Key Activities**

- Inspected the dataset structure and data quality.
- Identified and handled missing values.
- Reviewed NULL values in the `StoreClass` column.
- Standardized relevant store classification information.
- Prepared the cleaned dataset for Tableau visualization.

**Project Outcome**

The resulting dataset provides a more consistent foundation for analyzing store distribution and market presence across countries.

This project strengthened my understanding of how data quality and feature preparation influence the reliability of business analysis.

**Technology Stack:** Python, Pandas, Jupyter Notebook.

**Project Type:** Data Cleaning, Feature Engineering, Retail Analytics.

---

## 3. Business Intelligence & Dashboard Projects

### 3.1 Coffee Shop Sales Analysis — Microsoft Excel

**[View Excel Project](./coffeeOrdersData.xlsx?raw=true)**

**Dashboard Preview**

![Coffee Shop Sales Dashboard](./CoffeeOrdersDate.png)

**Project Overview**

This project analyzes coffee shop sales transactions to explore purchasing trends, product performance, and customer loyalty patterns.

The analysis was developed entirely in Microsoft Excel, combining data preparation, formulas, PivotTables, and dashboard visualization.

**Key Activities**

- Cleaned and organized transactional data.
- Handled missing values and improved data consistency.
- Created calculated columns for business analysis.
- Used PivotTables to summarize sales performance.
- Developed an interactive dashboard to monitor important sales indicators.

**Project Outcome**

The dashboard provides a practical overview of coffee shop operations and customer purchasing activity.

This project demonstrates how Excel can be used not only for spreadsheet management but also as a business intelligence tool for reporting and decision support.

**Technology Stack:** Microsoft Excel, PivotTables, Excel Formulas, Charts.

**Project Type:** Sales Analytics, Business Intelligence, Excel Dashboard.

---

### 3.2 H&M Global Store Network Analysis — Tableau

**[View Tableau Workbook](./ALL%20H%26M%20STORES%20WORLDWIDE.twbx)**

**Dashboard Preview**

![H&M Global Store Network Dashboard](./Dashboard.png)

**Project Overview**

Building on the cleaned H&M global store dataset, this project explores the company's international retail network and differences in store distribution across major markets.

The analysis focuses on understanding how store concentration and reported store classifications vary across countries.

**Key Activities**

- Analyzed global store distribution across countries.
- Compared store volumes in the top 20 markets.
- Examined reported store classifications.
- Developed dual-axis charts and stacked bar visualizations.
- Built a Tableau dashboard to communicate geographical retail patterns.

**Key Findings**

The visualizations suggest different market structures across regions, including a greater concentration of certain store classifications in major markets such as the United States and China, alongside dense store networks in established European markets.

These patterns provide a basis for exploring potential differences in retail market strategies. However, conclusions about investment priorities would require additional financial and operational evidence.

**Technology Stack:** Tableau, Python, Pandas.

**Project Type:** Business Intelligence, Retail Analytics, Market Analysis, Data Visualization.

---

## 4. SQL & Database Management

### 4.1 E-Commerce Sales Performance Analysis

**[View SQL Project](./E-commerce_sales%281%29.sql)**

**Project Overview**

This project demonstrates the use of SQL to retrieve, organize, and analyze e-commerce sales information stored in relational databases.

The objective was to practice writing SQL queries that can answer practical business questions and produce meaningful performance indicators.

**Key Activities**

- Filtered transaction records based on business requirements.
- Used SQL queries to retrieve relevant sales information.
- Aggregated transactional data for reporting.
- Analyzed sales performance across categories and time periods.
- Explored metrics related to revenue, growth, and profitability.

**Key Metrics**

- Total Revenue
- Sales Growth
- Profit Margin
- Sales Performance by Product Category

**Technology Stack:** SQL, PostgreSQL / MySQL.

**Project Type:** SQL Analytics, Database Management, Business Reporting.

---

## Education

**Universitas Langlangbuana (Langlangbuana University)**  
Bachelor's Degree in Informatics Engineering  
2023 – Present

**Areas of Interest:** Data Science, Machine Learning, Data Analysis, Database Systems, and Business Intelligence.

---

## Experience

### Junior Python Data Science
**PT VINIX SEVEN AURUM**  
February 2026 – June 2026

Gained practical exposure to Python-based data science workflows while further developing technical and analytical skills.

This experience supported my understanding of structured data processing, analytical problem-solving, and the application of Python in data-related projects.

---

## Certificates

I continuously develop my technical knowledge through courses, certifications, and hands-on projects.

| Field | Certification | Provider |
|---|---|---|
| Data Science | [Menjadi Data Scientist](https://www.dicoding.com/dicodingassets/coursecertificate/a433259bb6ecc5a45a5a6d0b7f859f53f17b9538/view) | Dicoding |
| Python | [Memulai Pemrograman dengan Python](https://www.dicoding.com/dicodingassets/coursecertificate/dc479dd3bfafd9d8d1e2fb528d46d501b00094e2/view) | Dicoding |
| SQL | [Structured Query Language (SQL)](https://www.dicoding.com/dicodingassets/coursecertificate/bd1868b980384c33942f4f716b49672e7231206e/view) | Dicoding |
| Software Engineering | [Introduction to Software Engineering](https://drive.google.com/file/d/1q5bWQSkuxcHv3tKJ_qqJPAlcrG41VWhl/view?usp=sharing) | Certificate |
| Machine Learning | [Machine Learning Bootcamp](https://drive.google.com/file/d/1DJiPYIlxAqu1VHB17LYm4JY2iYGV-boi/view?usp=sharing) | Certificate |

---

## Contact

I am open to opportunities in Data Analysis, Business Intelligence, Data Science, and related technology roles.

Feel free to connect with me to discuss projects, collaboration, or professional opportunities.

**LinkedIn:** [Ilsan Hidayatuloh](https://www.linkedin.com/in/ilsan-hidayatuloh-084465288/)

**GitHub:** [Ilsan08](https://github.com/Ilsan08)

**Email:** [hidayatullohilsan70@gmail.com](mailto:hidayatullohilsan70@gmail.com)

---

*Thank you for visiting my portfolio. I believe that working with data is not only about writing code or creating visualizations, but also about asking meaningful questions, understanding business problems, and finding insights that can support better decisions.*

**© 2026 Ilsan Hidayatuloh — Data Portfolio**
