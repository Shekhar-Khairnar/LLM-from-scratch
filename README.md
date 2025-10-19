# 🧠 LLM from Scratch — Notes & Code Implementation

GPT-2–style **124M-parameter** Transformer from scratch in PyTorch

This repository contains my detailed **implementations** from the _“Building LLMs from Scratch”_ YouTube series by **Raj Abhijit Dandekar (Vizuara)**, inspired by the book _Build a Large Language Model (From Scratch)_ by **Sebastian Raschka**.

The goal of this repo is to document a clear, hands-on understanding of how GPT-style models are built — covering everything from **tokenization** to **attention mechanisms** and **transformer blocks** using **PyTorch**.

---

## 📘 Contents

### 1️⃣ Tokenization

- Covers how **raw text data** is converted into tokens for model processing.
- Explains **Byte Pair Encoding (BPE)** and how merge operations build subword vocabularies.
- Step-by-step implementation using **Python** and **PyTorch**.
- Includes visual explanation of how tokens are generated and decoded back to text.

---

### 2️⃣ Attention

- Detailed breakdown of the **Attention Mechanism**, the core of modern transformers.
- Explains **Self-Attention**, **Scaled Dot-Product Attention**, and **Multi-Head Attention**.
- Implements **attention score calculations** and visualization of attention weights.
- Demonstrates how attention captures relationships across sequence context.

---

### 3️⃣ Transformer

- Full **step-by-step implementation** of a **GPT-style Transformer model**.
- Covers **positional embeddings**, **residual connections**, **layer normalization**, and **feed-forward networks**.
- Includes **PyTorch training loop** with **cross-entropy loss** and **perplexity evaluation**.
- Shows how each block fits together to form a complete decoder-only architecture.

---

## 💡 Highlights

- Explains each block of the model with **clear, commented code**.
- Focused on building intuition for **how transformers actually work**, not just running prebuilt libraries.
- Ideal for learners who want to **connect theory with implementation** and understand what happens under the hood of LLMs.

---

## ⚙️ Tools Used

- **Language:** Python
- **Framework:** PyTorch
- **Notebook Environment:** Jupyter / Colab
- **References:**
  - [Build LLM from Scratch series by Raj Abhijit Dandekar](https://www.youtube.com/watch?v=Xpr8D6LeAtw&list=PLPTV0NXA_ZSgsLAr8YCgCwhPIJNNtexWu)
  - _Build a Large Language Model (From Scratch)_ by **Sebastian Raschka**

---
