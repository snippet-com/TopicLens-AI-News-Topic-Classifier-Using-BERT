# TopicLens AI — News Topic Classifier Using BERT

## Overview

TopicLens AI is a Natural Language Processing (NLP) project that fine-tunes the `bert-base-uncased` transformer model to classify news headlines into predefined topic categories.

The project is built using the Hugging Face Transformers ecosystem and trained on the AG News dataset. It demonstrates the practical application of transfer learning and transformer-based architectures for text classification tasks.

---

## Features

* Fine-tuning of `bert-base-uncased`
* News headline topic classification
* Hugging Face Transformers integration
* Dataset preprocessing and tokenization
* Model training and evaluation
* Accuracy and performance metrics
* Google Colab compatible

---

## Dataset

This project uses the AG News Dataset available from Hugging Face Datasets.

### Categories

The dataset contains four news categories:

1. World
2. Sports
3. Business
4. Sci/Tech

Dataset Source:

* AG News Dataset from Hugging Face

---

## Technologies Used

* Python
* PyTorch
* Hugging Face Transformers
* Hugging Face Datasets
* Scikit-learn
* Google Colab

---

## Model Architecture

The project uses:

* `bert-base-uncased`
* Transformer encoder architecture
* Fine-tuning approach for supervised classification

### Workflow

1. Load dataset
2. Tokenize text data
3. Prepare train/test splits
4. Fine-tune BERT model
5. Evaluate model performance
6. Predict topic categories for unseen headlines

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/topiclens-ai.git
cd topiclens-ai
```

Install dependencies:

```bash
pip install transformers datasets torch scikit-learn
```

---

## Usage

Run the notebook in Google Colab or Jupyter Notebook.

### Open in Google Colab

Upload the notebook to Colab and execute all cells sequentially.

### Example Prediction

```python
headline = "Apple unveils next-generation AI chips"
```

Predicted Output:

```python
Sci/Tech
```

---

## Training Details

### Preprocessing

* Tokenization using BERT tokenizer
* Padding and truncation
* Attention masks generation

### Training

* Optimizer: AdamW
* Loss Function: CrossEntropyLoss
* Evaluation Metrics:

  * Accuracy
  * Precision
  * Recall
  * F1 Score

---

## Project Structure

```text
TopicLens-AI/
│
├── notebook.ipynb
├── README.md
├── requirements.txt
└── model_outputs/
```

---

## Future Improvements

* Add real-time news prediction API
* Deploy using Streamlit or Flask
* Experiment with RoBERTa and DistilBERT
* Add confusion matrix visualization
* Hyperparameter tuning
* Multi-language news classification

---

## Learning Outcomes

This project helps in understanding:

* Transformer architectures
* Transfer learning in NLP
* Fine-tuning pretrained language models
* Text preprocessing pipelines
* Deep learning for classification tasks

---

## Author

Moiz Malik

BS Artificial Intelligence Student

---

## License

This project is for educational and research purposes.
