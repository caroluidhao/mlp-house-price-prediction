# mlp-house-price-prediction

### Description
The dataset used on this predictive model is the result of the work of the the StatLib library about housing values in suburbs of Boston. This dataset can be accessed from the following website: [Boston Housing Data](https://archive.ics.uci.edu/ml/machine-learning-databases/housing/)

##### List of Features

    1) CRIM :     per capita crime rate by town
    2) ZN :       proportion of residential land zoned for lots over 25,000 sq.ft.
    3) INDUS :    proportion of non-retail business acres per town
    4) CHAS :     Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
    5) NOX :      nitric oxides concentration (parts per 10 million)
    6) RM :       average number of rooms per dwelling
    7) AGE :      proportion of owner-occupied units built prior to 1940
    8) DIS :      weighted distances to five Boston employment centres
    9) RAD :      index of accessibility to radial highways
    10) TAX :     full-value property-tax rate per $10,000
    11) PTRATIO : pupil-teacher ratio by town
    12) B :       1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
    13) LSTAT :   % lower status of the population

##### Dependent Variable

    14) MEDV :    Median value of owner-occupied homes in $1000's

### Dependencies
You can use `pip` or `conda` to install the dependencies:
- tensorflow
- matplotlib
- jupyter
- pandas
- seaborn
- scikit-learn

### Usage
If you want to try this program, download this repo and launch jupyter to run it on your machine. You can also check it out clicking on this link: [MLP Price Prediction](https://nbviewer.jupyter.org/github/igerardoh/mlp-house-price-prediction/blob/master/mlp-house-price-prediction.ipynb)

### - - - TODO  - - -
- ~~LOAD AND VISUALIZE THE RAW DATA~~
   - ~~Load the dataset and show statistic summary~~
   - ~~Visualize the data~~

- ~~DATA PREPROCESSING~~
   - ~~Apply standarization to features~~
   - ~~Apply one-hot encoding to categorical features~~
   - ~~Split data into training and testing sets~~

- ~~MODEL ARCHITECTURE~~
   - ~~Define network parameters~~
   - ~~Define network structure~~
   - ~~Define learning rate with different decaying methods~~
   - ~~Set up cost, optimizer, and accuracy function with different configurations~~
   - ~~Define model execution~~
   - ~~Visualize evolution of training and testing MSE through epoch iteration~~
   - ~~Visualize evolution of learning rate~~

- ~~OTHERS [OPTIONAL]~~
   - ~~Update README file~~
   - ~~Add log and summary writer~~
   - ~~Add Tensorboard visualization~~
   - ~~Add checkpoints for model restoration~~
