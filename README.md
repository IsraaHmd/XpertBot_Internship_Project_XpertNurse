# XpertBot_Internship_Project_XpertNurse
# 1 - Instructions for Getting Synthetic Data
-------------------------------------------------
- Download the Production Database:
URL: https://xpertbotacademy.online/xpertnurse_final.dump.zip
- Import the Database
- Restore the database dump into your local database environment (e.g., MySQL/PostgreSQL).
- After the import, export the tables as individual CSV files (you should have a folder containing CSVs like patients.csv, vitals.csv, etc.).
- Load the Data into Your Notebook/Script: Use your preferred method to load the CSV files (e.g., pandas.read_csv) so that they are available in your environment.
- Go to file phases1_and_2 and run the section called “Randomize the values in the Dataset”, it will randomize the loaded data to generate the synthetic dataset.


# 2- The Project has 5 phases: 
-------------------------------

PHASE 1: DATABASE UNDERSTANDING & EXPLORATION
----------------------------------------------
1. Restore SQL dump - Import and create ERD for patient management system
2. Data profiling - Analyze patients, medications, vitals, visits data
3. Schema documentation - Map relationships in healthcare data model
   
PHASE 2: DATA ANALYSIS
----------------------
5. Patient monitoring analysis - Vital trends over time, abnormal readings
6. Medication analysis - Most prescribed, adherence, interactions
7. Doctor performance - Visits, consultation time, case types
8. Care cycle analytics - Patient journey from admission to discharge

PHASE 3: ADVANCED INSIGHTS & MODELING
--------------------------------------
9. Health status classification - Categorize patients as stable/at-risk/critical
10. Temporal pattern mining - Detect recurring health events
11. Doctor recommendation system based on medical history
12. Patient clustering by diagnosis and care needs

PHASE 4: VISUALIZATION & REPORTING
----------------------------------
13. Interactive dashboard for vitals trends and doctor activity
14. Geo-health dashboard for regional illness patterns

Remark:
-------
For this phase, Streamlit and ngrok were used.
Ngrok: A tool that creates a secure public URL to expose your local web server (e.g., Streamlit app) to the internet.

PHASE 5: PREDICTIVE/RECOMMENDATION FEATURES
-------------------------------------------
16. Predict potential health decline using vital signs
17. Recommend preventive checkups based on health trends
18. Vitals anomaly alert classifier for automated alerting

3- Notes
---------
- The code of the phases are found in the .py and .ipynb files
- The ERD and Schema Documentation are in XpertBot Academy Internship_Phase1_ ERD_ Schema Documentation Pdf/Word Document.
