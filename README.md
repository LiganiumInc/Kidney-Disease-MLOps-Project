# Kidney-Disease-MLOps-Project


## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the dvc.yaml
10. app.py

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/LiganiumInc/Kidney-Disease-MLOps-Project.git
```
### STEP 01- Create a python environment after opening the repository

```bash
python3 -m venv kidney_env
```

```bash
source kidney_env/bin/activate
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

## MLflow

- [Documentation](https://mlflow.org/docs/latest/index.html)

- [MLflow tutorial](https://youtu.be/qdcHHrsXA48?si=bD5vDS60akNphkem)

##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/LiganiumInc/Kidney-Disease-MLOps-Project.mlflow \
MLFLOW_TRACKING_USERNAME=LiganiumInc \
MLFLOW_TRACKING_PASSWORD=5fddef3bd464e06d5aa57d95ad1be392a0a913fd \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/LiganiumInc/Kidney-Disease-MLOps-Project.mlflow

export MLFLOW_TRACKING_USERNAME=LiganiumInc

export MLFLOW_TRACKING_PASSWORD=5fddef3bd464e06d5aa57d95ad1be392a0a913fd

```