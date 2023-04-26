# peptide-parkinsons-challenge

Over the next few weeks, I will be working on the current kaggle challenge on predicting Parkinson's disease and updating this repository as I go. I am happy for others to copy my code, so long as I am acknowledged https://github.com/chris-hedemann/.
~C. Hedemann 26. April 2023

### Plan

* An extensive EDA process to 
  * reduce the number unnecessary peptides
  * fill in the many missing values for the UPDRS Unified Parkinsons Disease Rating Scale, especially UPDRS IV
* A Keras Long Short-Term Memory Network Baseline with a single layer as a baseline model for predicting future UPDRS scores based on in-serum peptide concentrations
* Increasing layer number and complexity, including dropout layers
* Programming pipelines to track model performance
