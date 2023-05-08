# peptide-parkinsons-challenge

This is a work in progress. As an exercise, I will be working on the current kaggle challenge on predicting Parkinson's disease and updating this repository as I go. See the link to the homepage
https://www.kaggle.com/competitions/amp-parkinsons-disease-progression-prediction/overview

It's a trick problem because there are over 1200 features and less than 1000 samples, so that the problem has a very high dimensionality and probably not enough data for training an NN. Nevertheless I am going to give training an LTSM NN a go.

### Notebooks in this repo

* Exploratory analyis including dimensionality reduction and feature engineering. Some peptide concentrations have little influence, some are best as binary features (present or not present), and some are best as concentrations. Completed.
* Training an LSTM: still in progress, with baseline model established.