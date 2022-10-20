# sample_sklearn_workflow
Sample sklearn workflow for a dataset with numerical and categorical data

I use the HistGradientBoostingClassifier model to classify the sklearn covtype dataset.
This repo focuses mostly on selecting the optimal feature selection strategies and preprocessing steps using GridSearchCV.
I didn't do much dataset exploration about the relationships between variables before developing the model, but the Titanic repo does have more of this type of work.

Each of the jupyter files are exploring one facet of the dataset.  In the order I made them:
1) initial_exploration.ipynb
2) scaling_experiment.ipynb
3) categorical_feature_selection.ipynb
4) num_dim_reduction.ipynb
5) predict.ipynb
