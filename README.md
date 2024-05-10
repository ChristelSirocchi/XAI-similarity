# Integrating Clinical Protocols in Machine Learning for Enhanced Interpretability and Continuity of Care

This repository contains the files associated with the manuscript titled "Integrating Clinical Protocols in Machine Learning for Enhanced Interpretability and Continuity of Care".

## Files

1. **pima_indians_imputed.csv**: This file contains the Pima Indians dataset, which was retrieved from [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database). The dataset has been preprocessed with median missing data imputation and utilized within the study.

2. **explanation_similarity_exp.ipynb**: This Jupyter Notebook provides the code to replicate all experiments conducted within the manuscript.

3. **ra_alpha_scores.csv**: This file records the performance scores with relative accuracy computed for integrated models with varying values of alpha.

4. **scores_alpha15.csv**: This file records the predictions for all models trained with alpha = 1.5.

5. **scores_cart_depth_leaves_all_correct.csv**: This file records the similarity metrics recorded for rule sets extracted from data-driven and integrated models of varying numbers of rules.

6. **all_robustness.csv**: This file records the robustness of the data-driven and integrated models for varying numbers of rules.
