# Predicting people's desire to have kids with dating app data

In this project I am using data collected from questions people answered on a dating app. The data is from [Kaggle](https://www.kaggle.com/datasets/andrewmvd/okcupid-profiles).

The dataset has a `offspring` column, that contains information about people's current number of children and their desire of having more children. I am going to use this column to make labels for the available data, and then I am going to build a classifier to see if it's possible to predict this information from the other columns in the dataset.

The project is divided in the following sections:
- **Exploratory data analysis**: look at data distribution, clean data, make new features
- **Feature selection methods**:
    - Filter methods: mutual information
    - Wrapper methods: forward/backward features selection, recursive feature elimination
    - PCA dimensionality reduction
- **Build model**: try different classifiers to see which one performs best with different sets of features
- **Conclusions**
