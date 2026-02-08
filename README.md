Health Clinic Data Summary & Outlier Analysis


 Overview

LifeCare Clinics collects daily patient vitals (blood pressure, heart rate, temperature, oxygen saturation).
Data is stored as CSVs, making it hard for doctors to spot high-risk patients.The system process 9 readings for each vital.
(note : outliers may appear in later readings, but for simplicity, the analysis uses the first reading.)

Objectives :

    - Build a Python-based data analysis pipeline for patient vitals
    - Ingest and clean raw CSV data
    - Calculate key statistics (Mean, Median, Mode) for each vital
    - Detect and flag outliers using the IQR method
    - Provide doctors with a clear summary of patients with abnormal readings

This project implements a Python pipeline that:

    - Cleans raw patient data
    - Calculates Mean, Median, Mode
    - Detects outliers using the IQR method
    - Flags patients requiring immediate attention

 Vitals Analyzed

    - Systolic Blood Pressure
    - Heart Rate
    - Oxygen Saturation
    - Body Temperature
    - Only the first reading per vital(reading 1 e.g Heart rate reading 1, Temperature reading 1 etc) 
     is used for consistent comparison. 

 Features 
    - Plain Python list was used
    - Mean, median mode was calculated manually 
    - Use of IQR for Outlier detection
    - Readabe structure

Project Structure 

-health-clinic-data-summary-Riliwan-Temitope/
│

├── data/patient_vitals.csv

├── Health_Data_Summary.ipynb

└── README.md

How to run The Project 

    - Clone the repository : 
        git clone <your-github-repo-link>
    - Click on project folder : 
        cd health-clinic-data-summary-riliwan
    - Open jupyter notebook to run the script 
        jupyter notebook Health_Data_Summary.ipynb

Author 
    Riliwan Temitope

