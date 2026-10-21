# SentimentScope 

A PyTorch-based sentiment analysis project that classifies IMDB movie reviews as **positive or negative** using a custom GPT-style transformer model.

## Technologies
- Python
- PyTorch
- Hugging Face Transformers
- Pandas and Matplotlib
- Jupyter Notebook

## Approach
- Loaded and explored the IMDB dataset containing 50,000 movie reviews.
- Implemented a custom PyTorch Dataset for tokenization and preprocessing.
- Built a transformer classifier using token embeddings, positional embeddings, multi-head self-attention, and a classification layer.
- Trained the model for 3 epochs using AdamW and cross-entropy loss.
- Evaluated performance using validation and test accuracy.

## Results

| Metric | Accuracy |
|---|---:|
| Final validation accuracy | 78.64% |
| Test accuracy | Pending evaluation |

## Getting Started

Install the dependencies:

```bash
pip install torch transformers pandas matplotlib scikit-learn jupyter
```

Download the [IMDB dataset](https://ai.stanford.edu/~amaas/data/sentiment/), then open and run `SentimentScope_starter.ipynb`.

## Key Takeaways
- Transformer architectures can be adapted for binary text classification.
- Data preprocessing and hyperparameter choices influence model performance.
- Separate validation and test sets help evaluate generalization.

## Dataset
[IMDB Movie Reviews Dataset – Stanford AI Lab](https://ai.stanford.edu/~amaas/data/sentiment/)
