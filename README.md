# High-Earner-classifier
•	Scope: predicted whether an individual income is more than $50k. <br />
•	Dataset: 32561 citizens/12 mixed attributes, CSV-format. <br />
•	The packages used: NumPy, Pandas, SciPy, Matplotlib/Seaborn, Scikit-learn. <br />
•	Cleaned the data: summarised them in histograms and box plots, kept outliers because of their rationality, transformed data anomalies (country, job). <br />
•	Challenge: considerable missing data (7.4%), replaced them with the mode. <br />
•	Algorithms: k-NN, Logistic Regression. <br />
•	Hyperparameter tuning increased their accuracy by 1.8% and 0.1% respectively.  <br />
•	Innovation: creating new features (e.g. retirement) has increased accuracy by 2% for both. <br />
•	Results: k-NN performed the best on the testing split giving 86% accuracy. <br />

The purpose of this data science project is to predict whether a randomly selected individual is a high earner with enough confidence. To do so, a dataset has been provided which outlines personal and financial information about a group of respondents in the United States. Knowing whether a group of individuals are wealthy is a critical information for various organisations: private companies, such as banks, seek it out to better target them; public companies to better understand them, and government agencies to better serve them. This dataset has been explored, pre-processed and prepared for a machine learning application. After building and tuning algorithms as well as engineering some of the features on the training data, the best algorithm has been chosen to forecast the target label on the unseen testing data. 

