# Sparse Attention Autoencoder for Anomaly Detection

## Abstract
Novel lightweight anomaly detection for time-series sensor data. Reduces false positive rates by 37% on SWaT, WADI, and DS2OS benchmarks.

## Key Innovations
- Dual-window scoring mechanism
- Sparse attention layer with O(n) complexity
- Unsupervised domain adaptation

## Results
| Dataset | F1-Score |
|---------|----------|
| SWaT    | 0.94     |
| WADI    | 0.91     |
| DS2OS   | 0.92     |

## Quick Start
`bash
pip install -r requirements.txt
python train.py
