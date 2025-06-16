# 🧠 Fine-Tuning Qwen 2.5-3B Instruct with LoRA on T4 GPU

This project demonstrates efficient fine-tuning of [Qwen 2.5-3B Instruct](https://huggingface.co/Qwen/Qwen2.5-3B-Instruct), a powerful LLM by Alibaba, using [LoRA](https://arxiv.org/abs/2106.09685) (Low-Rank Adaptation) and the [Unsloth](https://github.com/unslothai/unsloth) framework. It is optimized for low-cost GPUs like NVIDIA T4, using 4-bit quantization to reduce memory footprint.

---

## 🚀 Project Goals

- Fine-tune Qwen 2.5-3B efficiently on consumer-grade hardware (T4 GPU).
- Utilize **LoRA** for parameter-efficient tuning.
- Apply **Unsloth**’s optimized training engine for faster training and inference.
- Enable support for long-context reasoning and instruction-following tasks.
- Keep the solution simple, modular, and compatible with Colab or Kaggle environments.

---
