# Prompt Engineering with LLaMA 3 and Mistral

[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/prompt_engineering_llama3/blob/main/Prompt_Engineering_Llama3.ipynb)

Hands-on notebook for experimenting with **prompt engineering** and **in-context learning** techniques using **Meta LLaMA 3.1 8B** and **Mistral 7B** on the **CLinkaRT** clinical relation extraction dataset.

## 🧠 Project Goals

- Explore the behavior of large language models (LLMs) under few-shot and zero-shot prompting.
- Evaluate the impact of model size and instruction-tuning on in-context generalization.
- Compare performance and precision of **LLaMA 3.1 8B** vs **Mistral 7B** when reasoning over complex clinical sentences.

## 🧪 Models Used

- [Meta LLaMA 3.1 8B](https://ai.meta.com/llama/)
- [Mistral 7B](https://mistral.ai)

Both models are accessed via `transformers` and `unsloth` with support for memory optimization (e.g., 4-bit quantization, `bitsandbytes`, and `accelerate`).

## 📊 Dataset

We use the [CLinkaRT](https://github.com/HeidelTime/CLinkaRT) dataset, a benchmark for clinical relation extraction. The notebook formats the data into structured prompts suitable for instruction-following LLMs.

## 📄 License

This project is licensed under the **MIT License**.
