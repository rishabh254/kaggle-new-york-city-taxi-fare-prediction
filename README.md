# kaggle-new-york-city-taxi-fare-prediction
My solution of the New York City Taxi Fare Prediction competition of Kaggle.

To know more about the competition please follow the link: 
https://www.kaggle.com/c/new-york-city-taxi-fare-prediction

# Data:
The training data contains in 'train.csv' file and the testing data contains in the 'train.csv' file and the testing data contains in the 'test.csv' file. I am also adding a file 'data_description.txt' which contains the explanations of the fields available in the other data files.

To download the data please follow the links:
1. train.csv (https://www.kaggle.com/c/new-york-city-taxi-fare-prediction/download/train.csv)
2. test.csv (https://www.kaggle.com/c/new-york-city-taxi-fare-prediction/download/test.csv)

# Install:
To run this notebook:

1. Clone the repository.
2. Install [virtualenv](http://virtualenv.readthedocs.org/en/latest/installation.html).
3. Navigate to the directory where you unzipped or cloned the repo and create a virtual environment with `virtualenv env`.
4. Activate the environment with `source env/bin/activate`
5. Install the required dependencies with `pip install -r requirements.txt`.
6. Execute `ipython notebook` from the command line or terminal.
7. When you're done deactivate the virtual environment with `deactivate`.


# Dependencies:
* [NumPy](http://www.numpy.org/)
* [IPython](http://ipython.org/)
* [Pandas](http://pandas.pydata.org/)
* [SciKit-Learn](http://scikit-learn.org/stable/)
* [Seaborn](https://seaborn.pydata.org/)
* [Matplotlib](http://matplotlib.org/)
* [Keras](https://keras.io/)

I have been using kaggle kernels for this project. 
Here's my notebook : https://www.kaggle.com/rishabh254/nyc-ola/notebook

# Code:
[main.ipynb](https://github.com/rishabh254/kaggle-new-york-city-taxi-fare-prediction/blob/master/main.ipynb) : contains the whole code <br />
[eda.ipynb](https://github.com/rishabh254/kaggle-new-york-city-taxi-fare-prediction/blob/master/eda/eda.ipynb) : contains data exploration <br />
[cleaning.ipynb](https://github.com/rishabh254/kaggle-new-york-city-taxi-fare-prediction/blob/master/cleaning/cleaning.ipynb) : contains code to remove outliers <br />
[feature_engineering.ipynb](https://github.com/rishabh254/kaggle-new-york-city-taxi-fare-prediction/blob/master/feature_engineering/feature_engineering.ipynb) : contains code to extract new features <br />
[model1.ipynb](https://github.com/rishabh254/kaggle-new-york-city-taxi-fare-prediction/blob/master/models/model1.ipynb) : model for rides with variable fare <br />
[model2.ipynb](https://github.com/rishabh254/kaggle-new-york-city-taxi-fare-prediction/blob/master/models/model2.ipynb) : model for rides with almost constant fare

# Goal:
The goal for the competition is to predict the fare amount (inclusive of tolls) for a taxi ride in New York City given the pickup and dropoff locations.
