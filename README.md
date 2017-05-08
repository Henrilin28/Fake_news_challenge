# Fake News
Fake news challenge repo

##

Data Exploratory Analysis

For details of the task, see [FakeNewsChallenge.org](http://fakenewschallenge.org)


The data provided is `(headline, body, stance)` instances, where `stance` is one of `{unrelated, discuss, agree, disagree}`. The dataset is provided as two CSVs:


### `train_bodies.csv`

This file contains the body text of articles (the `articleBody` column) with corresponding IDs (`Body ID`)

### `train_stances.csv`

This file contains the labeled stances (the `Stance` column) for pairs of article headlines (`Headline`) and article bodies (`Body ID`, referring to entries in `train_bodies.csv`).

### Distribution of the data

The distribution of `Stance` classes in `train_stances.csv` is as follows:

|   rows |   unrelated |   discuss |     agree |   disagree |
|-------:|------------:|----------:|----------:|-----------:|
|  49972 |    0.73131  |  0.17828  | 0.0736012 |  0.0168094 |


#### Some task should be done in this projects


1. what is the keyword for each categories
2. take a look at the feature engineering from fnc-1 baseline
3. LDA, STM

Predictive modeling 

1. benchmark algorithm - fnc-1
2. deep learning - notebook/fakenews.ipynb
3. naive bayes
