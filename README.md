# **Project E5:** Red Wine Quality  
- # **Authors:**  
Sven-Erik Taru, Marten Tiisler, Tanel Tooming

- # **Motivation & Goal:**  
Wine quality plays a key role in both consumer satisfaction and producer decision-making. Traditional quality assessment requires human experts, which is slow, subjective, and costly. We aim to create a more objective approach using chemical measurements to estimate wine quality. Not only does this make the whole process quicker, but also cheaper. The main goal is to increase the consistency and objectivity of wine quality evaluation with a machine learning model that can predict the quality of wine based on given chemical properties. This can help save money and time.
The secondary goal is to identify which features have the strongest influence on the quality, as this can help winemakers make the necessary changes.
  
- # **Contents:**  
- **Data**  
*winequality-red.csv* - Red wine dataset used in our separate notebooks  
*winequality-white.csv* - White wine dataset used when comparing our models and their results  
- **Models**  
*RandomForest_Smote.ipynb* - The notebook used to create a Random Forest classifier model.  
*SVM_RBF.ipynb* - The notebook used to create the Support Vector Machine model.  
*xgbclass.ipynb* - The notebook used to create the XGBoost model.  
*WineQualityFinal.ipynb* - The final notebook that compares all three of our models and displays the results using different kinds of graphs.  
- **Extra**  
*RandomForestRegressor* - A notebook that was used to create a Random Forest Regressor model. However, we ended up not using this in any of the comparisons or the final results.  
*Correlation_matrix.ipynb* - A notebook that shows the correlations between all of the features in the dataset.  
*E5_report.pdf* - The PDF that we submitted as our homework 10 submission.  

- # **Replicating the analysis:**  
The analysis was conducted in Python 3.10 using Jupyter Notebook. The red and white wine datasets are provided as CSV files: *winequality-red.csv* and *winequality-white.csv*. These files are loaded directly into the analysis notebook using *Pandas*. To replicate the analysis, the user runs the *WineQualityFinal.ipynb* notebook from top to bottom. The notebook contains sections for data preprocessing, *SMOTE* application, model training, hyperparameter tuning, and evaluation.
