# Lab 03 - Azure Machine Learning, Automated ML, Model Lifecycle

## Objectives

- Describe Azure Machine Learning capabilities.
- Explain automated machine learning.
- Understand data, compute, jobs, models, and endpoints.
- Map the model lifecycle.

## Scenario

The retail company wants to build a custom churn model but does not yet have a large data science team. You must explain how Azure Machine Learning can support the workflow.

## Steps

### 1. Open Azure Machine Learning Studio

1. Open the Azure portal.
2. Search for `Azure Machine Learning`.
3. Open or create a training workspace if your instructor provides access.
4. Open Azure Machine Learning studio.

### 2. Identify Core Workspace Areas

Find and record:

```text
Data
Notebooks
Compute
Jobs
Models
Endpoints
Automated ML
```

### 3. Explain Automated ML

Write how AutoML helps with:

- Trying multiple algorithms.
- Selecting features.
- Evaluating models.
- Ranking model candidates.
- Producing a model for deployment review.

### 4. Map the Model Lifecycle

Create a flow:

```text
Collect data
Prepare data
Train model
Evaluate model
Register model
Deploy model
Monitor model
Retrain when needed
```

### 5. Choose Compute Safely

Discuss why training compute should match the lab size, budget, and workload.

## Validation

You should have a workspace area map, AutoML explanation, and model lifecycle flow.

## Cleanup

Delete any Azure Machine Learning workspace or compute resources created only for class if instructed.

## Checkpoint Questions

1. What is automated machine learning?
2. What is a model endpoint?
3. Why is model monitoring needed?
4. Why does compute choice affect cost?

## Exam Focus

Understand what Azure Machine Learning does at a high level: data, compute, training, automated ML, model management, deployment, and monitoring.
