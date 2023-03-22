# Health flow

An [Automate](https://llamalab.com/automate/) flow to keep track of health metrics and medical details. The metrics tracked by the flow are:

* Heart Rate
* Haemotocrit
* Eosinophils
* Basophils
* Lymphocytes
* Neutrophils
* Platelet Count
* Red Cell Count
* White Cell Count
* Mean Cell Haemoglobin
* Mean Cell Volume
* Mean Corpus Haemoglobin
* Red Blood Width
* Erythrocyte Sedimentation Rate
* Blood Pressure
* Weight
* Height
* Waist Circumference
* Body Fat
* Chest Circumference
* Hip Circumference
* Thigh Circumference
* Body Fat Mass
* Cholesterol
* Triglyceride
* Glucose
* Anion Gap
* Bicarbonate
* Chloride
* Potassium
* Sodium
* Urea
* Creatinine
* Vitamin B12
* Ferritin
* Thyroid-Stimulating Hormone
* Thyroid Peroxidase
* Eyesight
* vo2 Max
* Average spo2
* Sperm Motility
* Sperm Count 

## Components

The flow currently has three fibres: one for intialising the flow, one for fetching heart rate readings from a wearable devices, and another for getting manually-inputted health readings.

The flow uses [AutoWear](https://play.google.com/store/apps/details?id=com.joaomgcd.autowear&gl=US) to fetch information from a WearOS device.