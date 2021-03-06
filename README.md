# TMDB-Box-Office-Prediction
## Description
This project is made for Kaggle competition called TMDB Box Office Prediction.

The main goal is to predict overall worldwide box office revenue from films by exploring metadata on over 7,000 past films from The Movie Database (https://www.themoviedb.org/) and building Machine Learning models.

File "TMDB-Box-Office-Prediction.html" contains the sulution (download and open in browser for reading).  
File "TMDB-Box-Office-Prediction.ipynb" contains the sulution (kernel for running in jupyter notebook).  
Folder "Data" contains dataset.

## Data
Dataset contains 7398 movies and a variety of metadata obtained from The Movie Database (TMDB).  
Movies are labeled with id.

File "train.csv" - train data (3000 rows).  
File "test.csv" - test data (4398 rows).

Target feature is "revenue" in the "train.csv" file.  
We are predicting the worldwide revenue for 4398 movies in the test file.

## Requirements
Requirements for running the program:
- Python 3.3 or greater
- Jupyter-notebook
- Pandas
- Numpy
- Scikit-learn
- Matplotlib
- Seaborn
