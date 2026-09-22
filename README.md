# Disaster Image Classification

Team project: 4-class disaster image classification (Earthquake, Urban Fire, Landslide,
Water Disaster) with a fine-tuned EfficientNetB2, a SimpleConvNet baseline, and an
ensemble of the two.

## Open this first
- [`disaster_image_classification.ipynb`](./disaster_image_classification.ipynb) — the
  full pipeline: EDA → data preparation → modeling → ensembling → evaluation.

## Result (test set)
| Model | Accuracy | Macro-F1 |
|---|---|---|
| **EfficientNetB2** | **91.13%** | **0.9026** |
| SimpleConvNet | 81.96% | 0.8146 |
| Ensemble | 90.21% | 0.8942 |

Datasets used: [varpit94/disaster-images-dataset](https://www.kaggle.com/datasets/varpit94/disaster-images-dataset)
and [alex1994/natural-disaster-image-dataset](https://www.kaggle.com/datasets/alex1994/natural-disaster-image-dataset)
(not committed here).
