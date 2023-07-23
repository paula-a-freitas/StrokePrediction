Heart-related diseases affect millions of people around the world and, according to the World Health Organization (WHO), are the second leading cause of death in the world's population. As a data scientist, you have been hired to create a predictive model that, from patient data such as age, gender, glucose level, whether the patient smokes or not, will predict whether that patient will have a stroke or not.

You have access to a file that has patient attributes and a “stroke” attribute, which indicates whether that patient suffered a stroke event or not.

The stroke_data.csv dataset is available at:
    https://drive.google.com/file/d/163BGU_RzXR29UbVVkPpv8tYnUejlPBVr/view?usp=share_link.

Attribute Information
1) id: unique identifier
2) gender: "Male", "Female" or "Other"
3) age: age of the patient
4) hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
5) heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
6) ever_married: "No" or "Yes"
7) work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
8) Residence_type: "Rural" or "Urban"
9) avg_glucose_level: average glucose level in blood
10) bmi: body mass index
11) smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
12) stroke: 1 if the patient had a stroke or 0 if not
*Note: "Unknown" in smoking_status means that the information is unavailable for this patient