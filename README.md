Project Overview
The objective of this project was to evaluate the performance of different machine learning (ML), hybrid ML, and deep learning (DL) models in predicting dissolved oxygen (DO) levels using varying amounts of data and different input features. The study was conducted in two phases:

Using COD and Temperature as Inputs:

Models: Random Forest (RF), XGBoost (XGB), Hybrid Model (combining ML techniques), and Deep Learning (DL).
Data splits: Five splits with increasing amounts of data (1/5 to 5/5).
Using COD Only as Input:

Models: RF, XGB, Hybrid Model, and DL.
Data splits: Same five splits as in the first phase.
Phase 1: Using COD and Temperature as Inputs
Results:

Random Forest (RF): Performance improved steadily with more data, peaking at the fifth split.
XGBoost (XGB): Showed the highest performance in the second split but remained consistently high across all splits.
Hybrid Model: Performance improved significantly with more data, showing the highest score in the fifth split.
Deep Learning (DL): Performance was highest in the first split, then stabilized slightly lower but consistently good.
Analysis:

Consistency: XGBoost and DL models exhibited more consistent performance across different data splits compared to RF and the Hybrid model.
Sensitivity to Data Size: RF showed the greatest improvement with increasing data, suggesting it benefits more from larger datasets.
Peak Performance: DL and XGB had the highest initial performance, indicating their robustness even with smaller datasets.
Phase 2: Using COD Only as Input
Results:

Random Forest (RF): Performance fluctuated with a general decrease compared to using both inputs.
XGBoost (XGB): Performance decreased significantly when temperature was removed, showing more variability.
Hybrid Model: Maintained relatively high performance, with slight improvement in higher splits.
Deep Learning (DL): Maintained the highest consistency and overall performance, similar to the hybrid model but slightly better.
Analysis:

Feature Sensitivity: Removing temperature as an input negatively impacted all models, with RF and XGB experiencing the most significant drops.
Model Robustness: DL and the Hybrid model were more robust to the reduced feature set, maintaining higher performance levels.
Data Utilization: Despite the reduced feature set, increasing the data size still benefited all models, indicating the importance of data volume.
Conclusions
Model Performance:

Deep Learning: Consistently outperformed other models in both phases, showing robustness to both data volume and feature set changes.
XGBoost: High performance with all features, but more sensitive to feature reduction.
Random Forest: Benefited significantly from larger datasets but was more affected by feature reduction.
Hybrid Model: Showed a balanced performance, improving significantly with more data and maintaining robustness with fewer features.
Impact of Data Volume:

Increasing the amount of data generally improved model performance across all types, especially for RF and the Hybrid model.
Impact of Feature Set:

The inclusion of temperature as a feature significantly improved prediction accuracy. Removing temperature reduced the performance of all models, highlighting the importance of comprehensive feature selection.
This assessment provides a clear understanding of how different models respond to changes in data volume and feature sets, guiding future efforts in model selection and data collection strategies for predicting dissolved oxygen levels.
