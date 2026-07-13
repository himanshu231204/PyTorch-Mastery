# PyTorch Mastery — Beginner to Production Engineer

A single reference repo you can come back to at any stage: learning PyTorch for the
first time, revising before an interview, debugging a weird training bug, or
building a production-grade fine-tuning pipeline.

**How this repo is organized:** every topic is a single Jupyter notebook,
`topic_name.ipynb`, so the concept, runnable code, common bugs, and exercises
all live together in one place — no jumping between files. Each notebook
follows the same internal structure:

1. **Concept** (markdown) — the mental model: what it is, why it exists, when to reach for it
2. **Numbered code sections** (markdown explanation + runnable code cell, repeated) — minimal, heavily commented, actually executed
3. **Common bugs** (markdown) — the mistakes everyone makes here + how to diagnose them
4. **Exercises** (markdown + a scratch code cell) — problems to test you actually understood it

Open the notebook for your topic, read top to bottom, run the cells. When
something breaks in your own project, jump to that notebook's "Common bugs"
section before Googling — it's written for exactly that moment.

---

## Roadmap

### 00 — Setup
Environment, CUDA/CPU/MPS detection, project structure conventions, how to use this repo.

### 01 — Fundamentals (the stuff everything else is built on)
| Notebook | Covers |
|---|---|
| `01_tensors/tensors.ipynb` | creation, dtypes, devices, broadcasting, views vs copies, in-place ops |
| `02_autograd/autograd.ipynb` | `requires_grad`, computation graph, `backward()`, `grad_fn`, detaching, no_grad |
| `03_nn_module/nn_module.ipynb` | `nn.Module`, parameters vs buffers, `state_dict`, custom layers |
| `04_datasets_dataloaders/datasets_dataloaders.ipynb` | `Dataset`, `DataLoader`, collate functions, samplers, multi-worker loading |
| `05_optimizers_losses/optimizers_losses.ipynb` | SGD/Adam/AdamW internals, loss functions, LR schedulers |
| `06_training_loop_from_scratch/training_loop.ipynb` | writing the loop by hand before using any trainer abstraction |

### 02 — Core Deep Learning
| Folder | Covers |
|---|---|
| `01_mlp` | fully connected nets, activation functions |
| `02_cnn` | convolutions, pooling, receptive fields, image classifiers |
| `03_rnn_lstm_gru` | sequence modeling, vanishing gradients, packed sequences |
| `04_regularization` | dropout, weight decay, label smoothing, early stopping |
| `05_initialization` | Xavier/Kaiming, why bad init kills training |
| `06_debugging_and_visualization` | loss curves, gradient norms, hooks, tensorboard |
| `07_transfer_learning` | freezing/unfreezing, feature extraction vs fine-tuning |

### 03 — Advanced Architectures
| Folder | Covers |
|---|---|
| `01_attention_and_transformers` | self-attention, multi-head attention, encoder/decoder from scratch |
| `02_vision_transformers` | patch embeddings, ViT |
| `03_resnet_efficientnet` | skip connections, modern CNN backbones |
| `04_gans` | generator/discriminator training dynamics |
| `05_vaes` | latent variable models, reparameterization trick |
| `06_graph_neural_networks` | message passing, GCN/GAT basics |
| `07_diffusion_models` | forward/reverse diffusion, denoising objective |

### 04 — LLM Fine-tuning
| Folder | Covers |
|---|---|
| `01_huggingface_ecosystem` | `transformers`, `datasets`, `tokenizers`, `accelerate` |
| `02_full_finetuning` | full-parameter fine-tuning, memory math |
| `03_lora_qlora` | LoRA, QLoRA, PEFT internals, adapter merging |
| `04_prompt_and_instruction_tuning` | instruction datasets, chat templates |
| `05_rlhf_dpo` | reward modeling, PPO vs DPO |
| `06_quantization` | int8/int4, GPTQ/AWQ/bitsandbytes basics |
| `07_inference_optimization` | KV cache, batching, speculative decoding basics |
| `08_evaluation` | perplexity, task benchmarks, eval harnesses |

### 05 — Production Engineering
| Folder | Covers |
|---|---|
| `01_mixed_precision` | AMP, fp16/bf16, loss scaling |
| `02_distributed_training` | DataParallel vs DDP vs FSDP, multi-GPU basics |
| `03_experiment_tracking` | Weights & Biases / MLflow, checkpointing strategy |
| `04_model_serving` | TorchServe, FastAPI serving, batching requests |
| `05_onnx_torchscript_export` | exporting models for production runtimes |
| `06_testing_ml_code` | unit tests for data pipelines, models, training steps |
| `07_profiling_and_optimization` | `torch.profiler`, memory leaks, `torch.compile` |
| `08_reproducibility_and_config` | seeding, deterministic runs, Hydra/YAML configs |

### 06 — End-to-End Projects
Full pipelines that combine everything above: data → train → evaluate → serve.
1. Image classification pipeline (CNN, from raw images to served model)
2. Text classification pipeline (transformer encoder, HF `datasets`)
3. LLM fine-tuning project (QLoRA on an instruction dataset, end to end)
4. Recommendation system (embeddings + two-tower model)
5. Multimodal project (image + text)

---

## How to use this repo when you're stuck

1. Find the closest matching topic notebook.
2. Jump to its **Common bugs** section — most "why isn't this working" moments are already there.
3. Run the notebook's code cells and compare output to your own code.
4. If it's a production issue (OOM, slow training, distributed weirdness), go to `05_production_engineering` first — it's organized by symptom, not just topic.

## Status
This repo is being built incrementally, one notebook at a time. Completed
notebooks are checked below; everything else has a folder reserved and will
be filled in next.

- [x] `01_fundamentals/01_tensors/tensors.ipynb`
- [x] `01_fundamentals/02_autograd/autograd.ipynb`
- [ ] everything else (structure exists, content coming — built and confirmed with you one notebook at a time)
