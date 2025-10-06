# Fine-Tuning with Hugging Face

This repository contains the code and resources for **Chapter 9: Fine-Tuning AI Models** from the Udemy course _[Understanding, Testing, and Fine-tuning AI Models with HuggingFace](https://www.udemy.com/course/ai-with-huggingface/)_.

🎯 This project demonstrates how to fine-tune bert model using the **Hugging Face Transformers library**, building upon foundational concepts in machine learning, NLP, and model evaluation covered in earlier chapters.

---

## 🚀 Fine-Tuned Model Available on Hugging Face Hub

The model fine-tuned has been uploaded and is publicly available on Hugging Face:

👉 **[yilong-ai/bert-base-uncased-text-classification](https://huggingface.co/yilong-ai/bert-base-uncased-text-classification)**

You can load it directly using the `transformers` library:

```python
from transformers import AutoTokenizer, AutoModelForSequenceClassification

model_name = "yilong-ai/bert-base-uncased-text-classification"
tokenizer = AutoTokenizer.from_pretrained(model_name)
model = AutoModelForSequenceClassification.from_pretrained(model_name)
```

---

## 📚 What's in this project

- Understand the concept and importance of **fine-tuning pre-trained language models**.
- Learn how to prepare datasets for downstream tasks (e.g., text classification, sentiment analysis).
- Use Hugging Face's `Trainer` API to train custom models efficiently.
- Apply best practices for training configuration, including hyperparameter tuning.
- Evaluate model performance using metrics like accuracy, precision, recall, and F1-score.
- Save and share your fine-tuned model on the Hugging Face Hub.

---

## 🛠️ Technologies & Tools Used

- 🐍 **Python** – Programming language
- 🤗 **Hugging Face Transformers** – For loading and fine-tuning transformer models
- 🧪 **Datasets** – Hugging Face dataset library
- ⚙️ **Trainer & TrainingArguments** – High-level training API
- 📊 **Evaluate** – Model evaluation metrics
- 🧰 **Jupyter Notebook / Python scripts** – Code implementation
