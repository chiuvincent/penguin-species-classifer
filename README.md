# penguin-species-classifer
Group project written in Jupyter Notebook (`python`) that deployed machine learning models to predict penguin species.  
Imported and cleaned up `palmer_penguins.csv` dataset into 3 qualitative and 6 quantitative features.  
Conducted exploratory data analysis to gain understanding of feature distribution.  
Reserved 80% of dataset as training set and 20% of dataset as testing set.  
Deployed machine learning models in `scikit-learn` (random forest, neural network, logistic regression) on training set to select 2 quantitative and 1 qualitative feature, and chose complexity parameters.  
Used trained ML models to predict penguin species in testing set, achieving a score at least `0.985`.  
Generated confusion matrix and decision region for error analysis.
