# model-engineering
## Project
This project tries to predict the best Payment Service Provider for an online transaction.
It was implmented using the CRISP-DM cycle and split in three Jupyter Notebooks regarding the data preparation, the explorative data analysis and the modeling.
The modeling includes the training of different Machine Learning Models.
It compares them with HyperOpt and the optimizes the RandomForestClassifier with GridSearch.

## Get started
Create an environment with the required packages
```bash
conda create --name <env> --file requirementy.txt
```

Export conda env to requirements.txt
```bash
conda list -e > requirements.txt
```