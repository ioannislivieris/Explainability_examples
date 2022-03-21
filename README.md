# Explainability

An introduction to various frameworks and web apps to interpret and explain Machine Learning (ML) models in Python. A guide to 7 packages in Python to explain Your models
1. SHAP
2. LIME
3. SHAPash
4. ExplainableDashboard
5. Dalex
6. Explainable Boosting Machines
7. ELI5

All notebooks were implemented in Google Colab.


## Summary
Before methods such as SHAP and LIME became popular, the standard model explanations, with some interpretability (at a global-level), included methods such as 

- Variable Importance (different methodologies based on the ML algorithms), 
- Decision trees, 
- Partial Dependence Plots (PDP), 
- Individual Conditional Expectation plots (ICE) and 
- Classical Regression Coefficients. 

It is nothing but a human need to understand how something works before we gain comfort and trust in it. The classic trade-off of higher model complexity leading to less interpretability is now being contained. The presented new methodologies apply approaches such as creation of replicating models, which mimic the behaviour of the original models at a local scale and help explain how a certain prediction was made.




**Bonus code:** SHAP (SHapley Additive exPlanations) was introduced in 2017 by Lundberg and Lee and has been widely used by data scientists to explain predictive models through computing the contribution of each feature to a prediction. The SHAP summary plot is an interesting plot which shows both contribution of a feature in a prediction and its directionality (how it moves the target needle). 

Notebook: Converting insights from a SHAP summary plot.ipynb has an implementation with which all valuable insights from a SHAP summary plot into a data structure (e.g., pandas DataFrame) which allows to better explain predictive models.

