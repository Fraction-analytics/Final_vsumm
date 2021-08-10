# Deep Reinforcement Learning for Unsupervised Video Summarization with Determinantal point process.
# Implement with python = 3.x

## Requirement

python = 3.x

Pytorch

tabulate

## 1. Get Started
```bash
mkdir dataset and put mp4 video files 
```
## 2. Dataset Generation
```bash
python3 create_data.py --input videos --output dataset/data.h5
``` 
## 3. Feature Extraction
```bash
python feat_extraction.py -d dataset/data.h5
``` 
## 4. Summary Generation

```bash
python updated.py

```
Video summarization will be saved folder log/fraction.mp4
