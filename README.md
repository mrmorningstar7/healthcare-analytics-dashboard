# Healthcare Analytics Dashboard

## Project Overview
An interactive healthcare analytics dashboard analyzing hospital performance metrics, patient outcomes, and operational efficiency. This project uses synthetic data generated with Python.

## Files in this Repository
- `healthcare_analysis_dashboard_template.pbix`: Power BI dashboard template
- `healthcare_analysis.csv`: Synthetic healthcare dataset 
- `healthcare_analysis_dashboard.pdf`: PDF export of dashboard
- `healthcare_analysis_generation.ipynb`: Jupyter notebook for synthetic data generation

## Tools Used
- Power BI for dashboard creation and visualization
- Python for data generation and preprocessing
- Jupyter Notebook for code documentation
- Libraries: pandas, numpy, datetime

## Skills Demonstrated
- Data Analysis & Visualization
- Dashboard Design
- Time Series Analysis
- Healthcare Metrics
- Python Programming
- DAX Measures Creation
- Data Modeling
- Synthetic Data Generation

## Dashboard Features
### 1. Patient Care Overview
- Average Recovery Rate
- Average Recovery Rate by Hospital
- Treatment Success Rate by Doctor
- Average Length of Stay
- Average Length of Stay by Diagnosis

### 2. Cost Analysis
- Daily Cost Trends by Hospital
- Average Daily Cost
- Cost vs Recovery Rating
- Total Bill by Diagnosis

### 3. Operational Metrics
- Total Patients in 2025
- Total Patients in 2024
- Total Patients Last Quarter
- Total Patients Lifetime
- Doctor Workload Distribution
- Average Length of Stay by Month 

## How to Use
1. Clone or download this repository
2. Open the .pbix file using Power BI Desktop
3. Data connection will automatically reference the included CSV file
4. Explore the dashboard or use as a template!

## Data Dictionary
Key fields in the dataset include:
- `PatientID`: Unique identifier for each patient
- `AdmissionDate`: Date of patient admission
- `DischargeDate`: Date of patient discharge
- `LengthOfStay`: Duration of hospital stay
- `DailyCost`: Cost per day of stay
- `TotalBill`: Total cost of treatment
- `RecoveryRating`: Patient recovery score (1-10)
