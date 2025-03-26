# GPT2 Model Fine-Tuning for Health

This project demonstrates fine-tuning a GPT-2 model for health-related tasks using the Hugging Face Transformers library. The fine-tuned model is trained on a dataset of medical questions and responses to generate contextually relevant answers.

## Features

- Fine-tunes GPT-2 for health-related question-answering tasks.
- Uses the Hugging Face `transformers` library for model training and tokenization.
- Supports dataset preprocessing, tokenization, and training with evaluation.
- Saves the fine-tuned model for inference.

## Requirements

- Python 3.10 or higher
- Required libraries:
  - `transformers`
  - `datasets`
  - `torch`
  - `scikit-learn`

Install the dependencies using pip:

```bash
pip install transformers[torch] datasets scikit-learn
```

## Example

Prompt: Question: What are the symptoms of
Generated Text: Question: What are the symptoms of posttraumatic stress disorder? Output: This is a diagnosis that can be made at any age...