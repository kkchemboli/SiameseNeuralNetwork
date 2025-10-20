# Siamese Neural Network for Face Recognition

This project implements a **Siamese Neural Network** in [PyTorch](https://pytorch.org/) for one-shot image classification.  
Siamese networks are particularly useful for tasks where we have very few training examples per class (e.g., face verification, signature verification, or few-shot learning).

---

##  Getting Started

You can run this project either in **Google Colab** (recommended for simplicity) or locally using **Jupyter Notebook**.

### Clone the Repository

```bash
git clone https://github.com/kkchemboli/SiameseNeuralNetwork.git
cd SiameseNeuralNetwork
```
### Option 1: Google Colab (Recommended)

- Open the `.ipynb` file directly in [Google Colab](https://colab.research.google.com/).
- No installations are required — Colab comes with PyTorch pre-installed.
- You may need to adjust import paths slightly depending on your Colab directory structure.

### Jupyter Notebook (Local)
1.install required dependencies (use uv)
```bash
uv sync
```
2.Launch Jupyter Notebook:
```bash
jupyter notebook
```
---

##References
1.https://www.cs.cmu.edu/~rsalakhu/papers/oneshot1.pdf


