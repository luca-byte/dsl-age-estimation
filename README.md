The software developed for the regression task is included as jupyter notebooks.

In order to reproduce the described results, do the following:

1. Execute `data-preprocessing.ipynb`, it contains most of the preprocessing of the task
2. Execute  `model-hyper-param.ipynb`, it contains the model training and hyperparameter tuning

The notebook `data-preprocessing.ipynb` expects the dataset in the `data` folder 

```
data
├───development.csv
├───evaluation.csv
├───audios_development
└───audios_evaluation
```

In `model-hyper-param.ipynb` the files `proc/*-leaderboard.csv` are used to compare the scores of the cross-validation with the leaderboard scores. These files were created manually and are includer for your convenience.