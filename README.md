# End-to-end ML Pipeline via Mlflow 
This repository contains an end-to-end pipeline to estimate the typical price for a given property based on the price of similar properties. We utilize MLflow for pipeline management, Hydra for parameter configuration, and Weights & Biases for artifact tracking.

##Introduction
This project provides a comprehensive ML pipeline designed to predict property prices. By leveraging the power of MLflow, Hydra, and Weights & Biases, the pipeline ensures efficient model management, parameter configuration, and artifact tracking.

##Features
MLflow Integration: Seamlessly manage the entire ML lifecycle, from experimentation to deployment.
Hydra Configuration: Simplify parameter management and configuration with Hydra.
Weights & Biases Tracking: Track experiments, visualize results, and manage artifacts with Weights & Biases.

##Dataset
The dataset is a ppublic dataset, and can be found here https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data

##Installation
To set up the project, follow these steps:

### clone the repository:
git clone (https://github.com/Simogh67/ml_pipeline_mlflow.git)

### Create environment:
conda env create -f environment.yml

### Get API key for Weights and Biases
wandb login [your API key]