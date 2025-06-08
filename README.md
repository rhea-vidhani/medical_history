# medical_history

Key Highlights:
1. Created a normalized table structure with patient info, hospital visits, and billing data
2. Cleaned inconsistencies: uppercased names, fixed gender mislabels, removed invalid entries (e.g. PATIENT_ID = 21)
3. Performed custom queries to:
A. Identify top 5 patients by billing amount
B. Analyze age-based health conditions (e.g. 40+ patients)
C. Filter by gender, emergency cases, and medical conditions
D. List all distinct medical conditions
5. Ran advanced aggregations:
A. Avg. billing per condition
B. Patient counts by condition & gender
C. Emergency admissions by hospital
D. Stay duration and cost per night per patient
