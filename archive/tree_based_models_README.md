Logistic Regression and Tree based Models
  1) The dataset contains employee survey information. The goal was to predict what factors influenced the employee's decision to leave the company.
  2) The first part of the notebook contains EDA (cleaning dataset, visualizing correlations, identifying outliers (as regression models are susceptible to outliers))
  3) A logistic regression model was then built and evaluated.
  4) Feature engineering was impelemented before building out Tree based models
  5) Firstly, a decision tree was built and evaluated by implementing hyperparameter tuning using GridSearchCV.
  6) Since, decision trees are prone to overfitting, a RandomForest tree model was implemented
  7) The scores of all the models were compared and the test data was used on the champion model (in this case RandomForest model) to predict the outcomes.
  8) Lastly, The tree models were evaluated in detail by constructing the trees visually, identifying and implementing feature importance. 
