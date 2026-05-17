This repository contains PA 20.1 https://github.com/sabinadeparis/CAPSTONE_EDA_FINAL_Module20.git

PLEASE NOTE: Please note, as previously discussed and agreed, my certification is sponsored by my company; 
therefore, I am required to complete the capstone project using an internal business use case. 
Due to company confidentiality policies, I am not authorized to share the original dataset. 
However, I can provide a detailed description of the data, methodology, and results obtained throughout the project.

MAIN FINDING The baseline model uses Logistic Regression with time-based splitting because it is fast, interpretable, and suitable for both numerical and categorical insurance features; a Decision Tree Classifier will also be tested. The main evaluation metric is the F1-Score, supported by PR-AUC, since the dataset is highly imbalanced (many active policies vs few surrendered policies). Accuracy and ROC-AUC are not reliable here because a model predicting “no surrender” for all customers could still achieve very high accuracy. The F1-Score balances Precision and Recall: Precision reduces unnecessary retention actions, while Recall ensures actual surrender risks are detected. For example, an F1-score of 0.65 with 70% Precision and 61% Recall means the model correctly identifies most real lapse risks while limiting false alarms.
