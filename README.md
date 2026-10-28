
# OralSense 🦷

OralSense is an educational deep learning project for oral image
classification using a trained MobileNetV2 model.

## Features

- Image upload and classification
- Transfer learning with MobileNetV2
- Ranked prediction scores
- Interactive Streamlit interface

## Classes

- Calculus
- Caries
- Gingivitis
- Hypodontia
- Mouth Ulcer
- Tooth Discoloration

## Project Structure

```text
OralSense/
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
└── models/
    └── oralsense_model.keras
```

## Installation

Python 3.10 or 3.11 is recommended.

```bash
pip install -r requirements.txt
```

Place the saved model at:

```text
models/oralsense_model.keras
```

## Run the App

```bash
streamlit run app.py
```

## Model Results

| Model | Test Accuracy | Macro F1 |
|---|---:|---:|
| MobileNetV2 | 79.52% | 77.38% |
| EfficientNetB0 | 79.40% | 73.55% |

These are experimental results on the project's test split.

## Disclaimer

OralSense is an educational project, not a medical device.
It must not be used to diagnose or treat medical conditions.
