# Flu Shot Learning Datasets
The goal is to predict how likely individuals are to receive their H1N1 and seasonal flu vaccines. This repository contains 4 datasets: training_features, test_features, training_labels and submission.

You are provided a dataset with 36 columns. The first column respondent_id is a unique and random identifier. The remaining 35 features are described below.
For all binary variables: 0 = No; 1 = Yes.

For this competition, there are two target variables:

- h1n1_vaccine: Whether respondent received H1N1 flu vaccine.
- seasonal_vaccine: Whether respondent received seasonal flu vaccine.

Both are binary variables: 0 = No; 1 = Yes. 
Some respondents didn't get either vaccine, others got only one, and some got both. This is formulated as a multilabel (and not multiclass) problem.

More Information at https://www.drivendata.org/competitions/66/flu-shot-learning/page/211/
