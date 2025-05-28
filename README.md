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

#### Project 1: Predictive Modeling for Heart Disease Risk
* **Description:** This project focuses on developing and evaluating machine learning models to predict the likelihood of heart disease in patients based on a set of medical attributes. The analysis involves comprehensive exploratory data analysis (EDA) to understand feature relationships, data preprocessing including encoding and scaling, and the implementation of various classification algorithms. The final output includes a comparative evaluation of models like Logistic Regression, KNN, SVM, Naive Bayes, Decision Tree, Random Forest, and XGBoost, with a focus on identifying the most accurate predictive model. The insights derived help in understanding key risk factors associated with heart failure.
* **Skills Showcased:** Machine Learning, Data Visualization, Exploratory Data Analysis, Data Preprocessing, Model Building & Evaluation
* **[Link to Repository](https://github.com/dansarmiento/machine_learning_notebooks/blob/main/Heart_Failure_Prediction.ipynb) **

#### Project 2: Evaluating and Operationalizing an Appointment No-Show Prediction Model
* **Description:** This project centers on the comprehensive evaluation of a machine learning model designed to predict patient no-shows for medical appointments using data from an EPIC EHR system. The analysis includes retrieving and preparing appointment data, followed by a multi-faceted assessment of the model's predictive probabilities. Key evaluation steps involve examining the distribution of predictions across different appointment statuses, calculating standard classification metrics (ROC AUC, Precision, Recall, F1-score), and performing statistical tests (ANOVA, Tukey HSD) to confirm the model's ability to differentiate between outcome groups. The project also delves into model calibration by analyzing outcome frequencies within prediction percentile bins and segments performance by clinical specialty. The final output provides a clear understanding of the model's strengths and limitations, offering actionable recommendations for deploying tiered intervention strategies and dashboards to reduce no-show rates and enhance operational efficiency.
* **Skills Showcased:** Healthcare Analytics, Machine Learning Model Evaluation, Statistical Analysis (ANOVA, Tukey HSD), Data Visualization (Matplotlib, Seaborn), Data Retrieval (SQLAlchemy, SQL)
* **[Link to Repository](https://github.com/dansarmiento/analytics_portfolio/blob/main/EPIC_no_show_predict_evaluation.ipynb)**

#### Project 3: Machine Learning Modeling for Mental Health
* **Description:** This project demonstrates an end-to-end machine learning pipeline in Python to predict the likelihood of depression based on a range of lifestyle and demographic factors. It showcases the use of Pandas for data wrangling and a scikit-learn pipeline with a ColumnTransformer to handle imputation, scaling, and one-hot encoding for mixed data types before training and evaluating a Gaussian Naive Bayes classifier.
* **Skills Showcased:** Exploratory Data Analysis, Data Preprocessing, Naive Bayes, Data Visualization
* **[Link to Repository](https://github.com/dansarmiento/machine_learning_notebooks/blob/main/Naive_Bayes_for_Depression.ipynb)**

#### Project 4: dbt ETL build to modularize a patient profile report built in SQL
* **Description:** A dbt model that takes a SQL view creating a multi-faceted patient profile predicting churn with demographics data and modularizing it with dbt.
* **Skills Showcased:** dbt, SQL, Data Modeling
* **[Link to Repository](https://github.com/dansarmiento/dbt_data_build_tool)**
