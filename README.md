# Petals × LLaMA-2-70B — Distributed Inference + Prompt Tuning over the Internet

Running **LLaMA-2-70B** on a global **Petals** swarm for inference, and performing **prompt tuning** via swarm model-parallelism. This repo is a concise overview with links to full write-ups and exact commands.

*At a glance (stack): Petals · PyTorch · Transformers · Hugging Face Hub*

---

## Why this matters
Petals splits very large models across many volunteer/peer GPUs and stitches them together at runtime. That lets you **serve** or **tune** 70B-scale models without owning a single 80GB GPU. Peers can join/leave; Petals routes requests over the swarm.

---

## What’s in this repo
This is a **meta-repo** (README + links). For the exact scripts, flags, logs, and troubleshooting, use the two articles below.

---

## Links
- **Part 1 — Inference:** *Inferencing LLaMA-2-70B using Petals (swarm model parallelism over the internet)*  
  https://medium.com/@kannansarat9/part-1-inferencing-llama-2-70b-using-petals-swarm-model-parallelism-over-the-internet-a29de8f8aef3
- **Part 2 — Prompt Tuning:** *Prompt tuning LLaMA-2-70B using Petals (model parallelism over the internet)*  
  https://medium.com/@kannansarat9/part-2-prompt-tuning-llama-2-70b-using-petals-model-parallelism-over-the-internet-89cdee667840
