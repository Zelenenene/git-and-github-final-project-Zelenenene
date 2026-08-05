# git-and-github-final-project-Zelenenene

Final Project for MSE641
This repository contains the code and supporting materials for the final project of **MSE641**, which investigates spoiler type classification and spoiler generation for the Clickbait Challenge 2023.

## Project Overview

- **Task 1:** Spoiler type classification using transformer-based encoder models, including BERT and RoBERTa.
- **Task 2:** Spoiler generation using encoder-decoder transformer models, including BART and T5.

## Files

This repository contains multiple Jupyter notebooks and CSV files used for the experiments.

- **Jupyter notebooks** — Contain the implementations for spoiler type classification and spoiler generation.
  - Task 1 notebooks: Notebooks for Task 1 experiments. The notebook containing `final_model` in its filename corresponds to the final submission.
  - Task 2 notebooks: Notebooks for Task 2 experiments. The notebook containing `final_model` in its filename corresponds to the final submission.

- **CSV files** — Contain processed data and model prediction results.
  - CSV files with `prediction_task1` in the filename: Prediction results for Task 1. The file containing `best_score` in its filename corresponds to the final submission.
  - CSV files with `prediction_task2` in the filename: Prediction results for Task 2. The file containing `best_score` in its filename corresponds to the final submission.

Each notebook includes the corresponding preprocessing, model training, and evaluation pipeline.

## Environment

The experiments were conducted using:

- Google Colab (T4 GPU)
- Kaggle Notebooks (T4 GPU)


## Dataset

The project uses the Clickbait Challenge 2023 dataset.

## Notes

Random seeds were fixed where applicable. Due to the nondeterministic nature of GPU-based deep learning training, minor variations in results may occur across different runs.

## Author
Yuxin Zhong
