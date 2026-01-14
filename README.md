# AI & Machine Learning Coursework Projects

This repository contains my independent implementations for foundational AI tasks, focusing on Computer Vision (CV) and Natural Language Processing (NLP).

## 📂 Projects Overview

### 1. CIFAR-10 Classification with Lightweight ResNet (CV)
**Goal**: Design a lightweight CNN to outperform the LeNet baseline on image classification.

* **Architecture**: Built a custom ResNet from scratch using **PyTorch**.
* **Key Techniques**: Implemented **Residual Connections** and **Batch Normalization** to solve gradient vanishing.
* **Results**: Achieved a **27% accuracy improvement** over LeNet.
* **Analysis**: Conducted ablation studies on L2 Regularization and Dropout.

### 2. Sentiment Analysis with DistilBERT (NLP)
**Goal**: Apply Transfer Learning to classify sentiment and test model robustness.

* **Model**: **DistilBERT** (Hugging Face Transformers).
* **Strategy**: Compared **Feature Extraction** vs. **Fine-tuning**.
* **Results**: Fine-tuning paradigm achieved **93.55% accuracy**.
* **Robustness**: Tested with adversarial examples (sarcasm, double negatives) to analyze pragmatic limitations.

## 🚀 How to Run
Please open the `.ipynb` notebooks directly to view the code, experiments, and visualizations.