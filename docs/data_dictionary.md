# Data Dictionary: Obesity Estimation Dataset

This dictionary provides clear definitions and value scales for all features used in the analysis, based on the UCI Machine Learning Repository documentation.

## Core Features & Target Variable

| Feature | Description | Possible Values / Scale |
| :--- | :--- | :--- |
| **NObeyesdad** | **Target Variable:** Obesity level category (derived from BMI). | Insufficient, Normal, Overweight I/II, Obesity I/II/III |
| **Age** | Age of the participant. | Continuous (Years) |
| **Height** | Height of the participant. | Continuous (Meters) |
| **Weight** | Weight of the participant. | Continuous (Kilograms) |
| **Gender** | Participant's biological gender. | Male / Female |
| **MTRANS** | Primary mode of transportation. | Automobile, Motorbike, Bike, Public Transport, Walking |

---

## Coded Lifestyle & Habit Features

These features use numeric or text codes to represent frequency or intensity, which is critical for interpretation.

| Feature | Description | Possible Values / Scale |
| :--- | :--- | :--- |
| **FAVC** | Frequent consumption of high-calorie food. | Yes / No |
| **FCVC** | Frequency of vegetable consumption. | **1** = Never, **2** = Sometimes, **3** = Always |
| **NCP** | Number of main meals per day. | **1–2**, **3** (Majority), **>3** |
| **CAEC** | Snacking between meals. | No, Sometimes, Frequently, Always |
| **SMOKE** | Smoking status. | Yes / No |
| **CH2O** | Daily water intake. | **1** = <1 L, **2** = 1–2 L, **3** = >2 L |
| **SCC** | Monitoring calorie consumption. | Yes / No |
| **FAF** | Physical activity frequency. | **0** = None, **1–2** (Low/Moderate), **3** (High) |
| **TUE** | Technology usage time (Screen Time). | **0** = 0–2 hours, **1** = 3–5 hours, **2** = >5 hours |
| **CALC** | Alcohol consumption frequency. | None, Sometimes, Frequently, Always |