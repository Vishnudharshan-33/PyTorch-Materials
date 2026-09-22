# 🔥 Mastering PyTorch Tensors: The Foundation of Deep Learning

A concise, hands-on guide to PyTorch Tensors — the fundamental building blocks of every deep learning model. This notebook walks through tensor creation, attributes, arithmetic, reshaping, and NumPy interoperability with clear, runnable code examples.

## 📖 Overview

Tensors are like NumPy arrays, but supercharged for GPU acceleration. Whether you're just starting with PyTorch or need a quick refresher, this notebook covers everything you need to get comfortable working with tensors before diving into neural networks.

## 📑 Contents

- **Tensor Dimensions** — Scalars (0D), Vectors (1D), Matrices (2D), and Cubes (3D)
- **Special Tensor Creation** — `torch.rand()`, `torch.zeros()`, `torch.ones()`, `torch.arange()`, `torch.zeros_like()`, `torch.ones_like()`
- **Tensor Attributes** — shape, dtype, ndim, device, numel, and changing data types
- **Tensor Arithmetic** — element-wise operations, matrix multiplication (`torch.matmul` / `@`), and transposing
- **Aggregation** — min, max, sum, mean, argmin, argmax
- **Reshaping Tensors** — changing shape without changing data
- **NumPy ↔ PyTorch Interoperability** — `torch.from_numpy()` and `.numpy()`

## 🛠️ Requirements

- Python 3.8+
- [PyTorch](https://pytorch.org/get-started/locally/)
- NumPy
- Jupyter Notebook / JupyterLab

Install dependencies:

```bash
pip install torch numpy notebook
```

## 🚀 Usage

Clone the repo and launch Jupyter:

```bash
git clone https://github.com/Vishnudharshan-33/<repo-name>.git
cd <repo-name>
jupyter notebook PyTorch.ipynb
```

Run the cells sequentially to follow along with the examples.

## 🙋 Author

**Vishnu** — Data Engineer transitioning into AI Engineering
[GitHub](https://github.com/Vishnudharshan-33) · [LinkedIn](https://linkedin.com/in/Vishnudharshan-33)

## 📄 License

This project is open source and available for learning purposes. Feel free to fork and adapt it.
