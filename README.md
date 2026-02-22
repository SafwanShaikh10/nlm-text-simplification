# Text Simplification using Neural Language Models (NLM)

This project focuses on evaluating a Neural Language Model (T5-based) for
text simplification tasks, distinguishing between **mild** and **strong**
simplifications.

## Features
- Token-level accuracy evaluation
- Binary classification (mild vs strong simplification)
- ROC curve and AUC score
- Confusion matrix visualization
- Supports WikiLarge, ASSET, and TinySimplify datasets

## Project Structure
- `NLM.ipynb` – Training and experimentation notebook
- `run_evaluation.py` – End-to-end evaluation script
- `model_evaluation.py` – Detailed evaluation pipeline
- `QUICK_START_EVALUATION.py` – Plug-and-play evaluation cells

## Evaluation Metrics
- Token-Level Accuracy
- Classification Accuracy
- ROC-AUC Score
- Confusion Matrix

## How to Run
```bash
pip install -r requirements.txt
python run_evaluation.py
