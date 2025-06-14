# 🦙 llama

**Studying LLaMA‑2/LLaMA‑3 architecture by replicating it from scratch.**  
Implemented core components like Rotary Position Embeddings (RoPE), Gated Q-Activation (GQA), SwiGLU, and RMSNorm.

---

## 📚 Table of Contents

1. [Project Overview](#project-overview)  
2. [Features](#features)  
3. [Getting Started](#getting-started)  
4. [Usage](#usage)  
5. [Architecture Details](#architecture-details)  
6. [References](#references)  
7. [Contributing](#contributing)  
8. [License](#license)

---

## Project Overview

This repository is a hands‑on implementation of the LLaMA‑2/LLaMA‑3 model family, optimized for learning and experimentation. Built from the ground up to better understand LLM internals—including positional encodings, activation functions, and normalization layers.

---

## Features

- 📏 **Rotary Position Embeddings (RoPE)** – for context-aware attention positioning.  
- ⚙️ **Gated Q-Activation (GQA)** – improves representational capability.  
- 🔀 **SwiGLU Activation Function** – enhances nonlinearity in feed‑forward layers.  
- 📏 **RMSNorm** – efficient normalization for transformer blocks.  

(This is a learning-focused project—**not optimized for production**.)

---

## Getting Started

### Requirements

- Python 3.10+  
- PyTorch 2.0+ (or later)  
- NumPy  
