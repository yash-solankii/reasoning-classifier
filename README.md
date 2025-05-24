
# Reasoning Model Project

This repository contains resources for training and evaluating a reasoning classification model using the Mistral 7B architecture.

## Contents

- `datagen.ipynb`: Generates synthetic reasoning data.
- `finetune_mistral7b.ipynb`: Fine-tunes the Mistral 7B model on the reasoning dataset.
- `test.ipynb`: Tests the fine-tuned model.
- `reasoning_complexity_dataset.jsonl`: Dataset used for training.
- `mistral7b_reasoning_clf_optimized/`: Folder containing model checkpoints and related files.

## Getting Started

1. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

2. Run the notebooks in sequence to generate data, train, and evaluate the model.

## Notes

- Model checkpoints are large and may not be pushed to GitHub. Consider using Git LFS if needed.
