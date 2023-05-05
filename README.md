# Content-Based Recommender Project

## Project requirements:
- Python 3.7 - 3.9

## To install requirements:
```
pip install -r requirements.txt
```

## Project consist of:
- Data preparation (data_preparation directory with jupyter notebook)
- Dataset (dataset directory)
- Tools for evaluating and testing (evaluation_and_testing package)
- Amazon and Base Recommenders (recommenders package)
- Method for generating negative interactions (tools python file)

## What is done:
- [x] Data preparation in notebook
- [x] User features based on one-hot encoding
- [x] Item features based on one-hot encoding
- [x] Recommender based on user and item features

## Problems:
- [ ] I tried to prepare user and item features in another way e.g I tried
to use one-hot encoding on term and rate_plan columns, turn buckets into numbers
and agregate them but it gave me worse results. It was so bad that I decided not to
include it in the project. I think that it is because of the fact that there was 
inappropriate combinations of features. (e.g. some features had values in the range of 0-1 and some in the range of 0-200,
normalization didn't help)
- [ ] Other problem is performance of the model. I think it is because of the fact that
i prepared features in the worst way.