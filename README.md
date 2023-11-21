# machine_learning_project-unsupervised-learning-ChristinePavlik

## Project Outcomes
- Practice coding and implementing machine learning models, cleaning data, and interpreting results.

## Workflow:
- First, read the Wholesale_Data.csv datafile provided.
- Explore the data, identify missing values and outliers.
- Clean the data - normalize and scale the variables.
- Visualize relationships among explanitory variables.
- Use K-means Clustering, Hierarchical Clustering, and Principle Components Analysis to develop an unsupervised machine learning model to find the optimal number of groups to split the data into the maximize their similarity and minimize the overlap among them.
- Compare the outcomes of all the different models.
- Formulate inferences about the dataset using the models.

  ## Difficulties:

  I first included the categorical variables in the models, and it was only when I finished that I realized that the most interesting way that the data could be split (either by 'Channel' or 'Region') would be influenced very much by including those variables. I went back and took them out of all the models. As well, I wasn't sure whether it was worth scaling the data, as all the variables were measured in dollar amount and they were all quite similar. However, since we were not going to attempt to make inferences about specific spending habits, I opted to scale them.

  ## Key findings:

  I used three unsupervised Machine Learning Models to determine the best way to classify clients based on their annual spending habits within 6 categories: 'Fresh','Milk','Grocery','Frozen','Detergents_Paper','Delicassen'.

- There were no missing values in the dataset, and the variables were all non-normally distributed. We normalized and scaled them for modelling.
- There were no really substantial outliers once the data was normalized and scaled.
- None of the three unsupervised models classified the data particularly well. The best, which was a K-means cluster analysis, was able to explain only 28.9% of the variation seen in the dataset.
- All of the fitted models seemed to agree that the data was best split using only two clusters, which correlated to the variable 'Channel'. 
- The spending habits of Channel 1 and Channel 2 clients seem to be different, so effort should be made to market to each of them separately. 
