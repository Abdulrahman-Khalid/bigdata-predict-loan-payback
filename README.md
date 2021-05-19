# Load Prediction BigData
Using Spark and machine learning techniques, this is a model that predicts if a person would be able to pay back their requested loan.

Data is from [LendingClub](https://www.lendingclub.com/)

# Dependencies
- python3
- python3-pip
- Jupyter notebook

TODO

# Train Model
## Prepare Dataset
1. Download `accepted_2007_to_2018Q4.csv.gz` dataset from [kaggel](https://www.kaggle.com/wordsforthewise/lending-club?select=accepted_2007_to_2018Q4.csv.gz).
2. Move `accepted_2007_to_2018Q4.csv.gz` to `data/`.
3. `$ cd data`
4. `$ gunzip -k accepted_2007_to_2018Q4.csv.gz`

## Train Locally
Run all cells in `load_prediction.ipynb`.

## Train on a Cluster with Docker
TODO

# Inference
TODO
