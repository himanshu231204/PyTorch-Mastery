<h1 align="center">🔥 PyTorch Mastery — Beginner to Production Engineer</h1>

<p align="center"><b>The Complete PyTorch Reference — From Zero to Production</b></p>

<p align="center"><i>Learn every major PyTorch concept with hands-on notebooks, common bugs, and exercises — all in one place.</i></p>

<p align="center">
  <a href="https://github.com/himanshu231204/PyTorch-Mastery/stargazers"><img src="https://img.shields.io/github/stars/himanshu231204/PyTorch-Mastery?style=flat&logo=github&color=yellow" alt="Stars"></a>
  <a href="https://github.com/himanshu231204/PyTorch-Mastery/network/members"><img src="https://img.shields.io/github/forks/himanshu231204/PyTorch-Mastery?style=flat&logo=github&color=blue" alt="Forks"></a>
  <a href="https://github.com/himanshu231204/PyTorch-Mastery/blob/main/LICENSE"><img src="https://img.shields.io/github/license/himanshu231204/PyTorch-Mastery?style=flat&color=green" alt="License"></a>
  <a href="https://colab.research.google.com/github/himanshu231204/PyTorch-Mastery/blob/main/01_fundamentals/tensors.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue?style=flat&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat&logo=jupyter" alt="Jupyter">
  <img src="https://img.shields.io/badge/PyTorch-2.0+-red?style=flat&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat" alt="PRs Welcome">
</p>

<p align="center">
  <b>Part of the Mastery Series:</b>&nbsp;
  <a href="https://github.com/himanshu231204/ml-mastery">
    <img src="https://img.shields.io/badge/ML--Mastery-14%20⭐-ff9900?style=flat&logo=github" alt="ML Mastery">
  </a>
  <a href="https://github.com/himanshu231204/dl-mastery">
    <img src="https://img.shields.io/badge/DL--Mastery-3%20⭐-e74c3c?style=flat&logo=github" alt="DL Mastery">
  </a>
</p>

---

## Why PyTorch Mastery?

Most PyTorch tutorials give you either:

* 🔴 **Copy-paste code** with no explanation of *why* it works, or
* 🔴 **Dense academic papers** with no practical implementation

**These notebooks bridge that gap.** Every notebook gives you:

✅ Plain English explanation → ✅ Visual intuition → ✅ Runnable code → ✅ Common bugs → ✅ Exercises

Whether you are a **complete beginner** or an **experienced engineer** brushing up before an interview, this is your one-stop reference.

---

## Who is this for?

| 🎓 Students | 👨‍💻 Engineers | 🔥 Interview Prep |
|-------------|--------------|-------------------|
| Learning PyTorch from scratch with one structured, progressive path | Quickly look up syntax, parameters, and best practices mid-project | Concepts explained clearly + common interview Q&A covered in every notebook |

---

## Repository Structure

```
pytorch-mastery/
│
├── 00_setup/                              # Environment, CUDA/CPU/MPS detection
│
├── 01_fundamentals/                       # Core PyTorch building blocks
│   ├── tensors.ipynb                      # Creation, dtypes, devices, broadcasting
│   ├── autograd.ipynb                     # Autograd, computation graph, backward()
│   ├── nn_module.ipynb                    # nn.Module, parameters, state_dict
│   ├── datasets_dataloaders.ipynb         # Dataset, DataLoader, collate, samplers
│   ├── training_loop_from_scratch.ipynb   # Full training loop: batch, loss, backward, step
│   └── optimizers_losses.ipynb            # SGD/Adam/AdamW, loss functions, LR schedulers
│
├── 02_core_deep_learning/                 # Classical deep learning
│   ├── 01_mlp/                            # Fully connected nets, activations
│   ├── 02_cnn/                            # Convolutions, pooling, image classifiers
│   ├── 03_rnn_lstm_gru/                   # Sequence modeling, packed sequences
│   ├── 04_regularization/                 # Dropout, weight decay, label smoothing
│   ├── 05_initialization/                 # Xavier/Kaiming init
│   ├── 06_debugging_and_visualization/    # Loss curves, gradient norms, hooks
│   └── 07_transfer_learning/              # Freezing, feature extraction, fine-tuning
│
├── 03_advanced_architectures/             # Transformers, GANs, VAEs, diffusion
├── 04_llm_finetuning/                     # LoRA, QLoRA, RLHF, quantization
├── 05_production_engineering/             # AMP, DDP, serving, profiling
└── 06_end_to_end_projects/                # Full pipelines: data → train → serve
```

---

## 📚 Notebooks Quick Access

Click a notebook name to view it on GitHub, or the **Colab badge** to open it directly in Google Colab — no setup required.

### 🔥 01 — Fundamentals

| Notebook | What You'll Learn | Open |
|----------|-------------------|------|
| [`tensors.ipynb`](01_fundamentals/tensors.ipynb) | Creation, dtypes, devices, broadcasting, views vs copies, in-place ops | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/himanshu231204/PyTorch-Mastery/blob/main/01_fundamentals/tensors.ipynb) |
| [`autograd.ipynb`](01_fundamentals/autograd.ipynb) | `requires_grad`, computation graph, `backward()`, `grad_fn`, detaching, `no_grad` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/himanshu231204/PyTorch-Mastery/blob/main/01_fundamentals/autograd.ipynb) |
| [`nn_module.ipynb`](01_fundamentals/nn_module.ipynb) | `nn.Module`, parameters vs buffers, `state_dict`, custom layers | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/himanshu231204/PyTorch-Mastery/blob/main/01_fundamentals/nn_module.ipynb) |
| [`datasets_dataloaders.ipynb`](01_fundamentals/datasets_dataloaders.ipynb) | `Dataset`, `DataLoader`, collate functions, samplers, multi-worker loading | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/himanshu231204/PyTorch-Mastery/blob/main/01_fundamentals/datasets_dataloaders.ipynb) |
| [`training_loop_from_scratch.ipynb`](01_fundamentals/training_loop_from_scratch.ipynb) | Full training loop: batches, loss, `backward()`, optimizer step, eval | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/himanshu231204/PyTorch-Mastery/blob/main/01_fundamentals/training_loop_from_scratch.ipynb) |
| [`optimizers_losses.ipynb`](01_fundamentals/optimizers_losses.ipynb) | SGD/Adam/AdamW internals, loss functions, LR schedulers | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/himanshu231204/PyTorch-Mastery/blob/main/01_fundamentals/optimizers_losses.ipynb) |

### 🧠 02 — Core Deep Learning

| Notebook | What You'll Learn | Open |
|----------|-------------------|------|
| `mlp.ipynb` | Fully connected nets, activation functions, forward pass | 🔜 Coming soon |
| `cnn.ipynb` | Convolutions, pooling, receptive fields, image classifiers | 🔜 Coming soon |
| `rnn_lstm_gru.ipynb` | Sequence modeling, vanishing gradients, packed sequences | 🔜 Coming soon |
| `regularization.ipynb` | Dropout, weight decay, label smoothing, early stopping | 🔜 Coming soon |
| `initialization.ipynb` | Xavier/Kaiming, why bad init kills training | 🔜 Coming soon |
| `debugging.ipynb` | Loss curves, gradient norms, hooks, TensorBoard | 🔜 Coming soon |
| `transfer_learning.ipynb` | Freezing/unfreezing, feature extraction vs fine-tuning | 🔜 Coming soon |

### 🏗️ 03 — Advanced Architectures

| Notebook | What You'll Learn | Open |
|----------|-------------------|------|
| `attention_transformers.ipynb` | Self-attention, multi-head attention, encoder/decoder from scratch | 🔜 Coming soon |
| `vision_transformers.ipynb` | Patch embeddings, ViT | 🔜 Coming soon |
| `resnet_efficientnet.ipynb` | Skip connections, modern CNN backbones | 🔜 Coming soon |
| `gans.ipynb` | Generator/discriminator training dynamics | 🔜 Coming soon |
| `vaes.ipynb` | Latent variable models, reparameterization trick | 🔜 Coming soon |
| `gnn.ipynb` | Message passing, GCN/GAT basics | 🔜 Coming soon |
| `diffusion_models.ipynb` | Forward/reverse diffusion, denoising objective | 🔜 Coming soon |

### 🦙 04 — LLM Fine-tuning

| Notebook | What You'll Learn | Open |
|----------|-------------------|------|
| `huggingface_ecosystem.ipynb` | `transformers`, `datasets`, `tokenizers`, `accelerate` | 🔜 Coming soon |
| `full_finetuning.ipynb` | Full-parameter fine-tuning, memory math | 🔜 Coming soon |
| `lora_qlora.ipynb` | LoRA, QLoRA, PEFT internals, adapter merging | 🔜 Coming soon |
| `prompt_instruction_tuning.ipynb` | Instruction datasets, chat templates | 🔜 Coming soon |
| `rlhf_dpo.ipynb` | Reward modeling, PPO vs DPO | 🔜 Coming soon |
| `quantization.ipynb` | int8/int4, GPTQ/AWQ/bitsandbytes basics | 🔜 Coming soon |
| `inference_optimization.ipynb` | KV cache, batching, speculative decoding basics | 🔜 Coming soon |
| `evaluation.ipynb` | Perplexity, task benchmarks, eval harnesses | 🔜 Coming soon |

### ⚙️ 05 — Production Engineering

| Notebook | What You'll Learn | Open |
|----------|-------------------|------|
| `mixed_precision.ipynb` | AMP, fp16/bf16, loss scaling | 🔜 Coming soon |
| `distributed_training.ipynb` | DataParallel vs DDP vs FSDP, multi-GPU basics | 🔜 Coming soon |
| `experiment_tracking.ipynb` | Weights & Biases / MLflow, checkpointing strategy | 🔜 Coming soon |
| `model_serving.ipynb` | TorchServe, FastAPI serving, batching requests | 🔜 Coming soon |
| `onnx_torchscript.ipynb` | Exporting models for production runtimes | 🔜 Coming soon |
| `testing_ml_code.ipynb` | Unit tests for data pipelines, models, training steps | 🔜 Coming soon |
| `profiling_optimization.ipynb` | `torch.profiler`, memory leaks, `torch.compile` | 🔜 Coming soon |
| `reproducibility_config.ipynb` | Seeding, deterministic runs, Hydra/YAML configs | 🔜 Coming soon |

### 🚀 06 — End-to-End Projects

| Project | What You'll Build | Open |
|---------|-------------------|------|
| `image_classification` | CNN pipeline: raw images → served model | 🔜 Coming soon |
| `text_classification` | Transformer encoder + HF `datasets` | 🔜 Coming soon |
| `llm_finetuning` | QLoRA on an instruction dataset, end to end | 🔜 Coming soon |
| `recommendation_system` | Embeddings + two-tower model | 🔜 Coming soon |
| `multimodal` | Image + text | 🔜 Coming soon |

---

## 🧩 What's Inside Each Notebook

Every notebook follows this structure:

| Section | What You Get |
|---------|--------------|
| 📖 **Concept Overview** | Plain English explanation of what it is, why it exists, when to use it |
| 📐 **Math / Intuition** | The key equations and mental models behind the concept |
| 🔢 **Runnable Code** | Numbered sections — minimal, heavily commented, actually executed |
| ⚠️ **Common Bugs** | The mistakes everyone makes here + how to diagnose them |
| ✏️ **Exercises** | Practice problems with a scratch code cell to test your understanding |

---

## ⚡ Quick Start

```bash
# 1. Clone the repo
git clone https://github.com/himanshu231204/PyTorch-Mastery.git
cd PyTorch-Mastery

# 2. Create environment
conda create -n pytorch-mastery python=3.10 -y
conda activate pytorch-mastery

# 3. Install dependencies
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
pip install jupyter matplotlib numpy pandas

# 4. Launch Jupyter
jupyter notebook
```

Or — **skip all setup** and click any **Open in Colab** badge above.

---

## 🔧 When You're Stuck

1. Find the closest matching notebook in the tables above.
2. Jump to its **Common Bugs** section — most "why isn't this working" moments are already there.
3. Run the notebook's code cells and compare output to your own code.
4. For production issues (OOM, slow training, distributed weirdness) → check `05_production_engineering`.

---

## 📊 Status

This repo is being built incrementally, one notebook at a time.

- [x] `01_fundamentals/tensors.ipynb`
- [x] `01_fundamentals/autograd.ipynb`
- [x] `01_fundamentals/nn_module.ipynb`
- [x] `01_fundamentals/datasets_dataloaders.ipynb`
- [x] `01_fundamentals/training_loop_from_scratch.ipynb`
- [x] `01_fundamentals/optimizers_losses.ipynb`
- [ ] Everything else (structure exists, content coming — built and confirmed one notebook at a time)

---

## 📄 License

MIT — use it however you want.

---

<p align="center">Made with ❤️ for the PyTorch community. PRs and issues welcome!</p>
