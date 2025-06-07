
# 🚀 Transformer Miniatures

A compact and educational implementation of transformer architectures for learning and experimentation. These models are designed to be minimal, interpretable, and usable as a foundation for deeper exploration into transformer internals.

---

## 📘 Models

### 🔹 [Mini-GPT1 (Decoder-Only Transformer)](https://huggingface.co/dilip025/mini-gpt1)

A simplified GPT-style model built with only the decoder stack. Inspired by the original GPT-1 architecture, this model is trained using causal language modeling (CLM) and is suitable for small-scale text generation tasks or transformer training experimentation.

* **Architecture**: Decoder-only Transformer
* **Use Case**: Autoregressive text generation
* **Training Objective**: Causal Language Modeling (Next Token Prediction)
* **Tokenizer**: Byte-Level BPE
* **Framework**: PyTorch
* **Purpose**: Educational — ideal for understanding the GPT family of models

👉 [View on Hugging Face](https://huggingface.co/dilip025/mini-gpt1)

---

### 🔹 [RoBERTa-mini (Encoder-Only Transformer)](https://huggingface.co/dilip025/RoBERTa-mini)

A lightweight RoBERTa-style model using only the encoder stack. This model is pretrained using masked language modeling (MLM) and is useful for text classification, sentiment analysis, or as a fine-tuning base.

* **Architecture**: Encoder-only Transformer
* **Use Case**: Text understanding and classification
* **Training Objective**: Masked Language Modeling (MLM)
* **Tokenizer**: Byte-Level BPE (compatible with RoBERTa)
* **Framework**: PyTorch
* **Purpose**: Educational — to explore encoder-based pretraining and downstream task finetuning

👉 [View on Hugging Face](https://huggingface.co/dilip025/RoBERTa-mini)

---

## 🧠 Why These Models?

These mini models were built to:

* Provide hands-on insight into transformer architecture (decoder vs encoder)
* Support academic and hobbyist experimentation on limited hardware
* Serve as baseline models for testing new attention mechanisms or training schemes

---

## 📂 Repository and Code

If you want to see how these models were implemented from scratch, visit the ipynb file in this repo.

---

## 🙌 Acknowledgments

Inspired by:

* [GPT-1 by OpenAI](https://cdn.openai.com/research-papers/language-unsupervised/language_understanding_paper.pdf)
* [RoBERTa by Facebook AI](https://arxiv.org/abs/1907.11692)

Special thanks to the open-source NLP community!

---
