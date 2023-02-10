# Experiment Tracking with ML Flow

## Introduction

The process of building an end-to-end machine learning project involves collecting and processing raw data, analyzing features, training algorithms, evaluating models, and deploying the best model for user access. However, there are many complexities that arise along the way and the process becomes more about experimenting and trying out different things. Experiment tracking is the process of keeping track of all the relevant information from ML experiments.

## Purpose

The purpose of this experiment tracking system is to:
- Organize all the necessary components of a specific experiment in one place for easy access
- Reproduce past results using saved experiments

- Log iterative improvements over time, data, ideas, and teams


## Problem Statement
Imagine you are working at a finance company and are tasked with creating a machine learning model that classifies if an applicant should be given a loan based on certain conditions.

## Solution
We will be using the ML Flow library to keep track of all the relevant information from our machine learning experiments. With ML Flow, we can:

- Keep track of all the code, parameters, and results of each experiment
- Reproduce past results by re-running experiments with the same code, data, and parameters
- Compare the results of different experiments and choose the best model
- Store the code and models in a centralized repository for easy access

## Code
- The code Experiment_Tracking_MLFlow.ipynb is a sample experiment to classify loan applicants using the Random Forest algorithm. The code includes data processing, feature engineering, model training, and cross-validation.
 - It also contains images / snapshots to view the results as shown in mlflow
