# 🧠 PyTorch Deep Learning Foundations (From Scratch)

This repository demonstrates **core deep learning engineering skills** using **PyTorch**, built **from first principles** without relying on high-level abstractions.

The goal of this project is to show that I understand **how neural networks actually work**, not just how to use pre-built pipelines.

---

## 🚀 What This Project Covers

This project intentionally focuses on **fundamentals that every AI engineer must master**:

### ✅ Custom `nn.Module`
- Built neural networks by subclassing `torch.nn.Module`
- Explicitly defined layers and parameters
- Clear separation of model architecture and training logic

### ✅ Forward & Backward Pass
- Implemented forward pass using tensors and layers
- Used PyTorch **autograd** to compute gradients automatically
- Explained how gradients flow through the network

### ✅ Training Loop (From Scratch)
- Manual training loop with:
  - Forward pass
  - Loss computation
  - Backward pass
  - Optimizer step
- No training shortcuts or hidden abstractions

### ✅ GPU / Device Handling
- Device-agnostic code (`CPU ↔ GPU`)
- Safe `.to(device)` usage
- Seamless switching between CPU and CUDA (if available)

### ✅ Saving & Loading Models
- Saved trained model weights using `state_dict`
- Reloaded models for inference or continued training
- Demonstrated reproducibility and checkpointing

---

## 🧩 Project Structure
