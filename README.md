# machine_learning_project-supervised-learning-ChristinePavlik

## Project Outcomes
- Practice coding and implementing machine learning models, cleaning data, and interpreting results.

## Workflow:
- First, read the .csv datafile provided.
- Explore the data, identify missing values and outliers.
- Clean the data - replace missing values with means, inspect variables for outliers.
- Visualize relationships among explanitory variables and between dependants and independants.
- Use logistic regression to develop a classification model to distinguish between patients who had diabetes and patients who did not.
- Aggregate the outcome of other machine learning models into an ensemble model.
- Compare the performance of the original logistic regression and the ensemble model.

  ## Difficulties:

  As this is my first experience in using modeling to make predictions rather than interpret input parameters, it was a very interesting
  exercise. It's a totally new way to use models, and it was a huge learning experience.

  ## Key findings:

  In this exercise, the original logistic regression model performed the best. It was a fairly poor performing model, accurately predicting
  whether patients had diabetes or not only 76.6% of the time on novel data. However, the accuracy and type 2 error rate was similar between the training
  and test data, which indicates that the model was not overfitting the data. As well, there was high Type 2 error (false negative), which is
  extremely undesireable in a clinical test. The ensemble model did not improve on either the accuracy or Type 2 error rate over the
  logistic regression.

  ## If I Had More Time

  With more time, I would try a polynomial regression to see if a higher order logistic regression could improve the accuracy of the model. As well,
  I might try including interaction terms to the model, though none of the variables appeared highly correlated, there could have been a correlation
  between them that was not linear that might improve model performance.
