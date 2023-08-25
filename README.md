# masters-thesis
Machine Learning in Inflation Prediction for the Finnish Economy Dataset and Codes

The dataset available has been extracted from various sources and all the data belongs to the organization extracting it.

The analysis was conducted using the data from various sources and merged into one file. All the sources have been discussed in my Master's Thesis which is available in the <a href="https://doria.fi/handle/10024/187134">following repository</a>

There are two datasets where an initial dataset with five independent variables is used to train and predict the consumer price index. The dataset is the monthly dataset from January 2000 until January 2023. The additional dataset is where an additional 9 independent variables were added in order to test if the addition of variables impacted the results. They have been named 'Initial Data.csv' and 'Additional.csv' for analysis.

The original analysis was basic regression analysis with optimized and unoptimized parameters which can be found in 'Preliminary Analysis.ipynb' for 'Initial Data.csv' and 'Supplementary Analysis.ipynb' for 'Additional.csv'.

Cross Validation of the data with the used tools was performed on the files 'Cross_Valid_Preliminary.ipynb' and 'Cross_Valid_Supplementary.ipynb'. Feature importance was generated on the files named 'Preliminary_Feat_Imp.ipynb' and 'Supplemental_Feat_Imp.ipynb'.

The analysis utilizes the following regression algorithms:
<ul>
  <li>Decision Tree Regressor</li>
  <li>Random Forest Regressor</li>
  <li>LASSO (Least Absolute Shrinkage and Selection Operator) Regressor</li>
  <li>SVM (Support Vector Machine) Regressor (SVR)</li>
  <li>XGBoost (Extreme Gradient Boosting) Regressor</li>
  <li>MLP (Multi-Layer Perceptron) Regressor</li>
</ul>

The supplementary analysis has been optimized using parameters from the 'Initial data.csv' dataset as well as the 'Additional.csv' dataset therefore, there are two optimized results from these analyses.
