# Student-Depression-Evaluation

Project Summary

This project explores the factors contributing to mental health challenges among students. Using a dataset of student demographics and lifestyle habits, I developed a machine learning system to predict the likelihood of depression, aiming to identify at-risk students based on academic and personal stressors.

Key Insights

- Academic Pressure: Identified as one of the highest correlated factors with student depression.
- Sleep & Diet: Analyzed the significant role that lifestyle stability plays in mental well-being.
- Predictive Accuracy: Optimized models to ensure high recall, as missing a potential case (False Negative) is critical in mental health contexts.

Technical Workflow

- Data Cleaning: Handled categorical encoding for variables like `Gender`, `City`, and `Dietary Habits`.
- Statistical Analysis: Conducted feature correlation analysis using Seaborn and Scipy.
- Modeling: 
    - Logistic Regression: For baseline probability estimation.
    - Random Forest: For high-accuracy classification.
- Validation: Implemented ROC/AUC curves and Confusion Matrices to validate model sensitivity.

Results

The Random Forest model provided the most robust results, showing a strong ability to distinguish between depression risk levels based on the AUC score.

Technologies Used
- Python (Pandas, NumPy)
- Scikit-Learn (RandomForest, LogisticRegression, Metrics)
- Visualization: Seaborn, Matplotlib, Plotly
