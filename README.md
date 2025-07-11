📌 Problem Statement
Predict early signs of depression in students using behavioral data like screen time, phone usage, and questionnaire responses.

🛠 Tools & Technologies
Python, Scikit-learn

SHAP (SHapley Additive exPlanations)

Pandas, NumPy, Matplotlib

StudentLife Dataset

📈 Approach
Preprocessed app usage and phone activity logs.

Engineered behavioral features like unlock frequency and screen duration.

Trained a Random Forest classifier to predict depression risk.

Used SHAP to interpret feature contributions at both global and individual levels.

✅ Results
Achieved 1.0 ROC AUC, indicating a highly accurate model.

Identified screen time and PHQ-9 history as top predictors of depression risk.

Visualized feature importance using SHAP summary and beeswarm plots.
