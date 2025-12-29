# PyTorch Foundations

“Building strong PyTorch foundations before moving into GenAI systems.”


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



Each notebook includes:
- Clear section headers
- Short explanations before code
- Focus on *why* something is done, not just *how*

---

## Why I Built This

Before working on high-level frameworks and large models, I wanted to:
- Understand tensor behavior and memory
- Gain confidence in debugging shape, dtype, and gradient issues
- Write and reason about training logic myself

This foundation helps me move faster and debug better in real-world deep learning projects.

---

## Tools & Stack
- PyTorch
- Python
- Google Colab (GPU-enabled)
- Git & GitHub

---

## Next Steps
- Implement autograd examples in detail
- Write a training loop from scratch (no `Trainer` abstractions)
- Build a simple regression model to connect fundamentals to practice

---

> This repository reflects **learning depth and clarity**, not tutorial copying.
