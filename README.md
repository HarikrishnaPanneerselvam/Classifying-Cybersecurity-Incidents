🔧 Predicting Cybersecurity Incident Triage Grades

Overview

I built a machine learning model to predict cybersecurity incident triage grades: True Positive (TP), Benign Positive (BP), and False Positive (FP). This project helps SOCs (Security Operation Centers) work smarter by automating incident triage and improving enterprise security. 🚀

Key Features

🔐 Automates Triage: Saves time by classifying incidents automatically.

⚒️ Guided Responses: Provides actionable recommendations for SOC analysts.

🔒 Better Security: Reduces false positives and catches real threats faster.

Approach

📊 Data Exploration: Understand the dataset, features, and labels.

🌐 Data Prep: Handle missing data, encode categorical variables, and engineer useful features.

🎉 Model Training: Train advanced models like XGBoost and Random Forests.

🔄 Model Evaluation: Measure success with metrics like Macro-F1 Score, Precision, and Recall.

Dataset

The dataset has three levels:

Evidence: Metadata like IPs and emails.

Alerts: Groups of evidence showing potential threats.

Incidents: Multiple alerts forming a security event.

Train (70%) and Test (30%) sets are stratified to reflect real-world scenarios. 🔢

Metrics

🔢 Macro-F1 Score: Ensures balanced performance across classes.

📊 Precision: Reduces false positives.

🔓 Recall: Ensures critical threats are detected.

Results

Accurate triage-grade predictions 🔝.

Key insights into feature importance.

Ready-to-deploy model for SOC automation.

Tech Tags

#MachineLearning | #Cybersecurity | #SOC | #ThreatDetection 🚀
