# Parliamentary Speech Classification

This repository contains code and resources for analyzing and classifying parliamentary speeches. The primary objectives of this project are:

1. **Ideological Classification (Orientation)**: Identifying the ideological leaning (left or right) of the speaker's party based on their parliamentary speeches.
2. **Party Status Classification (Power)**: Determining whether the speaker’s party is currently in power or in opposition.

## Tasks Overview

### Task 1: Orientation Classification
- **Objective**: Predict the ideological stance of the speaker's party.
- **Classes**:
  - **Left (0)**: Speaker's party leans left.
  - **Right (1)**: Speaker's party leans right.
- **Dataset**: English-translated parliamentary speeches.

### Task 2: Power Classification
- **Objective**: Predict the governing status of the speaker’s party.
- **Classes**:
  - **Governing (0)**: Party is currently in power.
  - **Opposition (1)**: Party is in the opposition.
- **Dataset**: Original Turkish speeches.

## Repository Structure

The repository includes the following files:
- `test_ori.ipynb`: Notebook for testing the **original Turkish speeches** model.
- `test_power.ipynb`: Notebook for testing the **party status classification** model.
- `train_ori.ipynb`: Notebook for training the **ideology classification** model using original data.
- `train_power.ipynb`: Notebook for training the **party status classification** model.



