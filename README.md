# MLOPS-End2End
Creating this repo to revise the concepts of MLOPS



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

Clone the repository

```bash
https://github.com/Vijay-kumar-07/MLOPS-End2End
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n mlproject python=3.8 -y
```

```bash
conda activate mlproj
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
# Finally run the following command
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

MLFLOW_TRACKING_URI=https://dagshub.com/Vijay-kumar-07/MLOPS-End2End.mlflow \
MLFLOW_TRACKING_USERNAME=Vijay-kumar-07 \
MLFLOW_TRACKING_PASSWORD=e85530eeea963589bc3b9bb892b0a0b0e401e22b \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=:https://dagshub.com/Vijay-kumar-07/MLOPS-End2End.mlflow

export MLFLOW_TRACKING_USERNAME=Vijay-kumar-07 

export MLFLOW_TRACKING_PASSWORD=e85530eeea963589bc3b9bb892b0a0b0e401e22b

```



