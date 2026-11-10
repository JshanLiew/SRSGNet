# Scene-Adaptive Response Modulation and Structural Guidance Network for Building Extraction
**The code will be released soon.**

## Overview

We propose **SRSGNet**, a Scene-Adaptive Response Modulation and Structural Guidance Network. 

## Architecture
<img width="2409" height="1631" alt="main" src="https://github.com/user-attachments/assets/176a566e-939f-4c06-8c12-eb64d9b7386f" />

## Experimental Results

SRSGNet is evaluated on three widely used building extraction datasets:

- WHU Building Dataset
- Inria Aerial Image Labeling Dataset
- Massachusetts Buildings Dataset

Quantitative comparisons and ablation studies are provided in the paper.

## Training

To train SRSGNet, run:

```bash
python train.py
```

Please configure the dataset paths and training parameters before running the script.

## Evaluation

To evaluate the trained model, run:

```bash
python test.py
```

The evaluation script reports Precision, Recall, F1-score, and IoU.


