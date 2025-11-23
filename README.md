# **Scenario 1 – Land Cover Classification Pipeline**

### This repository contains my complete solution to Scenario 1 of the 6-month AI/ML Internship Selection Task–2025.
The project covers:

Q1: Geospatial preprocessing (grid creation, mapping, filtering)

Q2: Label extraction using ESA Land Cover

Q3: Training & evaluating a ResNet-18 classifier

All tasks have been completed in a fully reproducible pipeline built using PyCharm, GeoPandas, Rasterio, PyTorch, and TorchMetrics.

## **Repository Structure**
```
Scenario1_Project/
│
├── Scenario1_Pipeline.py   #It covers the Q1 and Q2 except the class distribution(done in scripts/plot_class_distribution) and imbalance discussion(done in report)
├── make_coords_and_labels.py
├── q1_finalize.py
│
├── data/
│   ├── rgb/                # Input RGB images (not uploaded)
│   ├── land_cover.tif      # ESA WorldCover (not uploaded)
│   └── image_coords.csv
│
├── outputs/                # Final results (all deliverables included)
│   ├── grid_60km.geojson
│   ├── grid_centroids.geojson
│   ├── grid_corners.geojson
│   ├── grid_plot_with_corners.png
│   ├── grid_satellite_map.html
│   ├── filtered_image_coords.csv
│   ├── q1_counts.txt
│   ├── labels.csv
│   ├── train_labels.csv
│   ├── test_labels.csv
│   ├── class_distribution.png
│   ├── train_test_distribution.png
│   ├── best_resnet18.pth
│   ├── confusion_matrix.png
│   ├── classification_report.txt
│   ├── metrics.csv
│   ├── metrics_summary.txt
│   ├── 5_correct_5_incorrect.png
│   ├── training_log.txt
│   └── class_presence.csv
│
└── scripts/
    ├── train_eval_resnet.py
    ├── plot_class_distribution.py
    └── plot_train_test_distribution.py

```
## How to reproduce everything:
###
