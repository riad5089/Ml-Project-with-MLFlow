# Ml-Project-with-MLFlow


## Workflows

1. Update config.yaml
2. Update schema.yaml
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the app.py


# How to run?

### STEPS:

clone the repository

```bash
https://github.com/riad5089/Ml-Project-with-MLFlow.git
```

### STEP 01- create a virtual environment after opening the repository

```bash
python -m venv mlproj
```

```bash
mlproj\Scripts\activate
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
python app.py
```

Now,
```bash
open up you local host and port
```


## MLflow

[Documentation](https://mlflow.org/docs/latest/index.html)


##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/riad5089/Ml-Project-with-MLFlow.mlflow
MLFLOW_TRACKING_USERNAME=riad5089 \
MLFLOW_TRACKING_PASSWORD=b98a37ee98e9d59a346135f14cb8ee568bc00c8b  \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/riad5089/Ml-Project-with-MLFlow.mlflow

export MLFLOW_TRACKING_USERNAME=riad5089 

export MLFLOW_TRACKING_PASSWORD=b98a37ee98e9d59a346135f14cb8ee568bc00c8b

```
