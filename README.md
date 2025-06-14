# Analytics Portfolio Repository
# Daniel Sarmiento | Analytics Engineer
[Chino, CA](https://www.google.com/maps/place/Chino,+CA) | (909) 973-8783 | dansarmiento@gmail.com | [LinkedIn](https://www.linkedin.com/in/DanSarmiento/) | [GitHub](https://github.com/dansarmiento/analytics_portfolio)

---

### About Me

Senior Data Analyst and Analytics Engineer with extensive experience in the healthcare sector. I specialize in designing and deploying cloud-based data solutions that integrate clinical, financial, and operational data to support business intelligence and data-driven decision-making. My expertise lies in architecting robust ETL/ELT pipelines, developing predictive models, and creating intuitive dashboards that empower stakeholders and drive organizational improvements. I am passionate about mentoring and leading teams in analytics engineering best practices.

---

### Skills

* **Cloud Data Platforms:** AWS Solutions Architect, Google Cloud Platform, Microsoft Fabric
* **Databases:** SQL Server, Postgres, MySQL, Google BigQuery, AWS Redshift 
* **ETL/ELT:** dbt, SQL, Python, Apache Airflow, Apache Kafka 
* **Programming Languages:** Python, SQL 
* **Data Visualization:** Tableau, Power BI, Google Looker 
* **Machine Learning:** Supervised and unsupervised model training with Python 
* **Version Control:** Github 
* **Epic Ecosystem:** Clarity, Caboodle, and Cogito Data Models 

---

### Portfolio Projects

*A curated selection of projects demonstrating my skills in data engineering, predictive analytics, and business intelligence. All projects use publicly available, de-identified data.*

#### Project 1: Building a Scalable E-Commerce Data Warehouse with dbt and BigQuery
* **Description:** This project demonstrates a complete, production-style analytics engineering workflow to build a data warehouse for a model e-commerce business ("Jaffle Shop"). Starting with raw data extracted from Google Sheets, the project involves loading the data into Google BigQuery and using the Data Build Tool (dbt) to perform robust, version-controlled transformations. The project showcases the evolution from a simple, monolithic SQL model to a scalable, multi-layered architecture, including staging models for data cleaning, intermediate models for complex logic, and final mart tables optimized for business intelligence and analysis. The final output is a clean, reliable, and well-documented data warehouse ready for analytics.
* * **Skills Showcased:** Analytics Engineering, Data Modeling (Staging, Intermediate, Marts), Data Transformation (ELT), dbt (Data Build Tool), Google BigQuery, SQL, Data Warehousing, Version Control Principles.
* **[Link to Repository](https://github.com/dansarmiento/analytics_portfolio/blob/main/dbt_bigquery_in_colab.ipynb) **

#### Project 2: Evaluating and Operationalizing an Appointment No-Show Prediction Model
* **Description:** This project centers on the comprehensive evaluation of a machine learning model designed to predict patient no-shows for medical appointments using data from an EPIC EHR system. The analysis includes retrieving and preparing appointment data, followed by a multi-faceted assessment of the model's predictive probabilities. Key evaluation steps involve examining the distribution of predictions across different appointment statuses, calculating standard classification metrics (ROC AUC, Precision, Recall, F1-score), and performing statistical tests (ANOVA, Tukey HSD) to confirm the model's ability to differentiate between outcome groups. The project also delves into model calibration by analyzing outcome frequencies within prediction percentile bins and segments performance by clinical specialty. The final output provides a clear understanding of the model's strengths and limitations, offering actionable recommendations for deploying tiered intervention strategies and dashboards to reduce no-show rates and enhance operational efficiency.
* **Skills Showcased:** Healthcare Analytics, Machine Learning Model Evaluation, Statistical Analysis, Data Visualization, Data Retrieval (SQLAlchemy, SQL)
* **[Link to Repository](https://github.com/dansarmiento/analytics_portfolio/blob/main/EPIC_no_show_predict_evaluation.ipynb)**

#### Project 3: Comparative Analysis of Machine Learning Models for Depression Prediction
* **Description:** This project demonstrates an end-to-end pipeline for predicting depression by comparing the performance of multiple machine learning models. The workflow includes comprehensive exploratory data analysis (EDA), robust data preprocessing using a scikit-learn ColumnTransformer, and handling of significant class imbalance with SMOTE. The core of the project involves training, tuning with GridSearchCV, and evaluating three distinct classifiers: Logistic Regression, Random Forest, and XGBoost, ultimately identifying the most effective model for this classification task.
* **Skills Showcased:** Exploratory Data Analysis, Data Preprocessing & Pipelines, Data Visualization, Class Imbalance Handling, Model Comparison & Evaluation, Logistic Regression, Random Forest, XGBoost.
* **[Link to Repository](https://github.com/dansarmiento/analytics_portfolio/blob/main/predict_depression_models.ipynb)**

#### Project 4: Machine Learning Patient Appointment Feature Store Design 
* **Description:** Designed and implemented a prototype feature store using Python and SQLite to manage, version, and evaluate features derived from patient appointment data. This project involved defining a comprehensive metadata model for feature definitions, transformation logic, feature sets, lineage, and evaluation metrics. The workflow included ingesting raw appointment data, performing feature engineering (e.g., extracting time-based features, creating categorical and boolean flags), registering these features, storing them, and conducting illustrative evaluations (Chi-Squared tests) against a target variable ("Left without seen"). The system also included visualization of feature distributions and evaluation results to aid in feature understanding and selection for potential predictive modeling.
* **Skills Showcased:** Python, Pandas, SQLite, Data Modeling, Feature Engineering, Machine Learning Feature Evaluation, Data Visualization, Metadata Management
* **[Link to Repository](https://github.com/dansarmiento/python_analytics_solutions/blob/main/Feature%20Store%20Modeling.ipynb)**
