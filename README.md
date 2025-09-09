

## 📰 Task 3: News Headline Classification Using BERT

### 🎯 Objective

Build and deploy a machine learning model that classifies news headlines into predefined topic categories using a fine-tuned **BERT transformer** model.

---

## 📚 Dataset

- **Name**: AG News Dataset  
- **Source**: Available via the [Hugging Face Datasets](https://huggingface.co/datasets/ag_news) library  
- **Description**: A collection of news headlines categorized into four topics: World, Sports, Business, and Science/Technology.

---

## ⚙️ Project Workflow

### 1. Data Preparation
- Load the AG News dataset using the `datasets` library from Hugging Face
- Clean and tokenize the text using the `bert-base-uncased` tokenizer

### 2. Model Fine-Tuning
- Use the `bert-base-uncased` model from Hugging Face Transformers
- Fine-tune it on the tokenized AG News dataset for multi-class text classification

### 3. Model Evaluation
- Evaluate the model’s performance on the test set using:
  - **Accu**
