# MVP-STG
Dual-Stage Multi-View Spatiotemporal Fusion Network for Cellular Traffic Prediction
## Basic Information

This repository contains the PyTorch implementation of **MVP-STG**, a Dual-Stage Multi-View Spatiotemporal Fusion Network for cellular traffic prediction.

MVP-STG is designed to model complex spatial-temporal dependencies in cellular traffic data by integrating multi-view feature extraction and fusion mechanisms for accurate traffic forecasting.
## Environment Setup

The implementation of MVP-STG was developed and tested under the following environment:

* torch>=2.0.0
* numpy>=1.21.0
* pandas>=1.3.0
* scipy>=1.7.0

## Repository Structure

```text
model/
├── model.py
├── data_loader.py
├── metrics.py
├── config.py
├── train.py
├── test.py
├── requirements.txt
├── .gitignore
├── README.md
└── data/
    ├── coords.csv
    ├── call_in.csv
    ├── call_out.csv
    ├── sms_in.csv
    └── sms_out.csv
```

## Dataset Access
We appreciate the availability of these public datasets, which can be accessed through the following sources.

* The Milan Telecom Dataset is available at https://www.nature.com/articles/sdata201555.
