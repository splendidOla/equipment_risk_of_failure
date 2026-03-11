# equipment_risk_of_failure
High-accuracy predictive maintenance model using Python and Scikit-learn. Combines structured service data with NLP-extracted features from industrial logs to predict equipment failure with 99%+ accuracy.

# Description
This project focuses on reducing operational downtime by predicting equipment failure through historical service data and technical narratives. By integrating structured costs and dates with unstructured job logs, the model identifies the specific precursors to machine breakdown. This allows organizations to move from reactive repairs to a proactive maintenance strategy, significantly saving on labor and parts costs.

# My Contributions
In this project, I developed a robust predictive pipeline that combines traditional numerical data with text-mined insights from service logs. I performed extensive feature engineering on "Job Types" and "Service Narratives," using text analysis to identify high-risk keywords like "breakdown" and "repair" which I then used as significant predictors in the model. I addressed significant data quality issues, such as missing values in service summaries, and achieved an exceptional model performance with an ROC AUC of 0.9998. My work provided a clear statistical link between specific service history patterns and the likelihood of future equipment failure, offering a direct tool for industrial decision-making.

# Methodology
Data cleaning and missing value imputation, feature extraction from unstructured service narratives, logistic regression with coefficient analysis for factor identification, binary classification for failure flagging, and model evaluation using Precision-Recall curves and ROC AUC.

# Tools Used:
Python, Pandas, Scikit-learn, Matplotlib, Seaborn, and NLP-based feature engineering.


# Key Features
1. Text-Augmented Predictive Modeling: Extracts features from unstructured "Job Types" and "Service Narratives" to improve prediction accuracy.
2. Failure Propensity Analysis: Identifies that approximately 24.7% of entries signify imminent failure based on historical patterns.
3. High-Precision Classification: Achieved an accuracy of 99.4% and an ROC AUC of 0.9998, ensuring highly reliable alerts for maintenance teams.
4. Interpretability: Uses logistic regression coefficients to rank which technical terms (e.g., "breakdown," "follow-up") are the strongest indicators of risk.
