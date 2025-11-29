# Decoding Gun Violence with Machine Learning

This repository contains an extensive analysis of gun violence data using various **Machine Learning** models, aiming to uncover key contributing factors, trends, and predictive insights. 

**Key Questions / Hypotheses**
As part of our project objectives, we focus on the following guiding research questions and/or hypotheses:

1. How do demographic, situational and contextual factors (e.g. race, age, education, place of incident) shape both the reason for gun incidents and the likelihood of police involvement?  
2. Are there underlying behavioural or demographic patterns, revealed through clustering, that distinguish different groups of gun incidents? Do these patterns align with the classification outcomes?  
3. Can machine learning models reliably identify the key risk factors that differentiate suicides, homicides, accidental shootings and undertermined cases? Do these risk factors reveal broader social or demographic trends observable in the dataset?   

---

## Repository Structure

### Project Structure

#### Data 📊

* `Guns incident Data.csv` - The primary raw file, found on the Kaggle website.
* `guns_incident_data_cleaned.csv` - The resulting dataset after data imputation.  
* `guns_encoded` - The resulting dataset after one-hot encoding to convert categorical columns into numerical columns.

#### Source Code
* `01_cleaning.ipynb` - Analyse missing values, decide method of data imputationg, as well as performing one-hot encoding
* `02_eda.ipynb` - Exploratory Data Analysis of the dataset

##### Models 🧠
###### Supervised Models
* `03_police_involvement_analysis` - Model aims to identify the key factors influencing police involvement in gun incidents. 
* `04_classifying_reasons_for_gun_incidents` - Model aims to predict the causes of these gun incidents
* `05_risk_profile_analysis.ipynb` - Finds combinations of features that best explain high-risk vs low-risk incidents.

###### Unsupervised Models
* `06_hierarchical_clustering.ipynb` - Initial exploration of clustering with a sub sample of the dataset
* `07_kprototypes_clustering.ipynb` - Deep dive clustering analysis.

