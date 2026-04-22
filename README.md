# CS6140_ML_Final_Project_Film_Budget_Prediction
## Project Details
**Class:** CS6140 Machine Learning\
**Semester:** Spring 2026\
**Author:** Margaret Bertoni\
**University:** Northeastern University

## Project Description
**Project Goal:** Predict the budget of a film given key characteristics of the film, including genre and runtime\
**Models Evaluated:**\
*Linear Regression with Basis Expansions with scikit-learn\
*Random Forest Regression with scikit-learn\
*Deep Neural Networks with Pytorch\

## Dataset
The dataset used was **The Ultimate Film Statistics Dataset - for ML** from [Kaggle](https://www.kaggle.com/datasets/alessandrolobello/the-ultimate-film-statistics-dataset-for-ml). The raw download is contained in the csv: [movie_statistic_dataset.csv](movie_statistic_dataset.csv). The dataset was pre-processed using a [Claude Project](https://claude.ai/share/dd861f84-3589-4b08-acaf-685ef80ebb41). The pre-processed dataset is in the csv: [movie_statistic_dataset_processed_buckets.csv](movie_statistic_dataset_processed_buckets.csv)

## Runtime Instructions
The analysis performed was broken out into individual Jupyter Notebooks for organization and to decrease runtime of individual notebooks. The analysis can be re-ran in the following files: \
**Linear Regression** [Linear_Regression](Linear_Regression.ipynb) \
**Random Forest Regression** [Random_Forest](Random_Forest.ipynb) \
**Deep Neural Networks ReLU** [NN_ReLU](NN_ReLU.ipynb) \
**Deep Neural Networks Leaky ReLU** [NN_Leaky_ReLU](NN_Leaky_ReLU.ipynb) \

Packages used include pandas, torch, torchmetrics, and matplotlib.pyplot. If you are missing any of these packages, you will need to install them to run this locally.  

