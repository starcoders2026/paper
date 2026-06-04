# Sky Innovators Forest Management

This repository contains the experimental notebooks, dataset information, and result reports for the study:

**Transfer Learning for Forest Image Classification
Using EfficientNet-B2**

The project includes three image classification modules:

1. Forest / Non-Forest Classification
2. Forest Density Classification
3. Fire / No-Fire Classification

All models were trained using EfficientNet-B2 with ImageNet pretrained weights.
The experiments were conducted in Kaggle notebook environments.

## Repository Structure

- `datasets/`: Kaggle dataset links and dataset descriptions
- `notebooks/`: Training notebooks for each classification module
- `results/`: Experiment result reports, including metrics, confusion matrices, and training curves
- `paper/`: This folder contains the academic paper related to this forest management classification study.

## Results Summary

| Module | Test Accuracy | Macro F1-score |
|---|---:|---:|
| Forest / Non-Forest Classification | 99.73% | 0.9954 |
| Forest Density Classification | 93.04% | 0.9026 |
| Fire / No-Fire Classification | 99.80% | 0.9922 |

## Notes

The reported results show internal test performance on prepared datasets.
The models have not yet been tested on fully independent external drone, aerial, or satellite datasets.
