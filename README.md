# PyTorch Foundations

This repository documents my hands-on learning of PyTorch fundamentals, with a focus on building strong intuition before moving to larger deep learning and GenAI models.

The goal of this repo is **not model performance**, but **deep understanding of how PyTorch works under the hood**.

---

## What I Covered

### 1. Tensor Fundamentals
- Creating tensors using `torch.empty`, `torch.zeros`, `torch.ones`, `torch.rand`
- Understanding tensor shapes, dtypes, and memory behavior
- Tensor indexing, slicing, and basic mathematical operations
- Device placement (CPU vs GPU) using Google Colab

📁 `tensors/`
- `01_pytorch_tensor_basics.ipynb`

---

### 2. Autograd & Gradient Flow *(in progress / next step)*
- `requires_grad` and computation graphs
- Backpropagation using `.backward()`
- Why and when gradients become `None`
- Disabling gradient tracking with `torch.no_grad()`

📁 `autograd/`

---

### 3. Environment & GPU Usage
- Verifying PyTorch version and CUDA availability
- Running computations on GPU (Tesla T4 in Colab)
- Understanding device-related errors and fixes

---

## How This Repo Is Structured
