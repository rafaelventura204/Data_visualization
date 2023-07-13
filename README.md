# Data_visualization
Covid patient data analysis and visualization

The project consists of the development of the visualization and analysis of a dataset containing clinical information of 300 patients who have contracted COVID-19 in different forms.

It was developed using an instance of Jupyter Notebook, specifically Google Colab

After visualizing the data graphically, it was studied using a machine learning model, whether a patient will survive or not.
to achieve this goal, the features of our dataset were used but given that
we can't take them all, let's apply Boruta, a feature selection algorithm.

#We apply the algorithm first to categorical data and then to normalized numerical data.

How does it work?
We start by highlighting in the dataset a set X (starting feature) and a set y (target variable).

We permute the feature values and create shadow feature attributes.

We apply Random Forest to find the feature acceptance threshold in X.

With a binomial distribution, you find which feature is actually significant and which you can leave out.
