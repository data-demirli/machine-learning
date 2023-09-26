# Predicting High Fire Areas in Montreal

## Summary:

**Dataset:** The dataset is a list of building fire incidents in the city of Montreal spanning from Jan 2015 to Sept 2022. Includes features relating to the incident and to the corresponding census tract area, collected from multiple sources.  
**Model:** Classifies the census tract areas (out of 540) which are expected to have a high number of fires per sq km in the following month. Random Forest and Logistic Regression model generated and compared. XGBoost added in appendix.  
**Particulars:** Feature engineering, feature selection, hyperparameter tuning, feature selection, imbalanced dataset, time lags, ROC curves

## [Table of Contents:](https://github.com/data-demirli/machine-learning/tree/main/0.%20Tree%20Based%20Methods/predicting-fires/predicting_fires_(xgboost_added).ipynb)

* Section 0 - Custom Functions
* Section 1 - Data Preparation and Feature Engineering
* Section 2 - Exploratory Analaysis
* Section 3 - Data Preprocessing
* Section 4 - Feature Selection
* Section 5 - Hyperparamater Tuning
* Section 6 - Baseline Predictions
* Section 7 - Final Model Results
* Appendix - XGBoost

## [Interactive Dashboard - Model Predictions:](https://public.tableau.com/views/ModelResults-HighRiskFireAreasMontreal/Dashboard?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
<div class='tableauPlaceholder' id='viz1677615047607' style='position: relative'><noscript><a href='https://public.tableau.com/views/ModelResults-HighRiskFireAreasMontreal/Dashboard?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link'><img alt='Dashboard ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Mo&#47;ModelResults-HighRiskFireAreasMontreal&#47;Dashboard&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='ModelResults-HighRiskFireAreasMontreal&#47;Dashboard' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Mo&#47;ModelResults-HighRiskFireAreasMontreal&#47;Dashboard&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
