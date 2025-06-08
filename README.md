# medical_history

Key Highlights:
1. Created a normalized table structure with patient info, hospital visits, and billing data
2. Cleaned inconsistencies: uppercased names, fixed gender mislabels, removed invalid entries (e.g. PATIENT_ID = 21)
3. Performed custom queries to:
 • Identify top 5 patients by billing amount
 • Analyze age-based health conditions (e.g. 40+ patients)
 • Filter by gender, emergency cases, and medical conditions
 • List all distinct medical conditions
4. Ran advanced aggregations:
 • Avg. billing per condition
 • Patient counts by condition & gender
 • Emergency admissions by hospital
 • Stay duration and cost per night per patient
