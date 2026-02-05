---
title: "Low-Resource Tigrinya Language Modeling with LoRA-Fine-Tuned GPT-2"
summary: "Fine-tuning GPT-2 using LoRA for low-resource Tigrinya language text generation with reproducible and robust training pipelines."

tags:
- Large Language Models
- GPT-2
- LoRA
- Low-Resource NLP
- Text Generation

date: 2025-01-01

image:
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/abrhaleyarefaine1997/gpt2-tigrinya-lora

slides: ""
---

## Overview
This project focuses on **low-resource language modeling** for **Tigrinya**, using parameter-efficient fine-tuning techniques applied to **GPT-2**.

The goal was to build a **reproducible, stable, and efficient** text generation system suitable for scarce-data settings.

## Methods
- Fine-tuned **GPT-2 (124M parameters)** using **Low-Rank Adaptation (LoRA)**
- Designed data preprocessing pipelines for sequential text modeling
- Controlled training stability and reproducibility through fixed seeds and logging
- Optimized memory usage and training efficiency

## Challenges Addressed
- Extremely limited labeled data
- High risk of overfitting in low-resource settings
- Evaluation of generative quality beyond loss metrics

## Results
- Generated coherent and grammatically consistent Tigrinya text
- Demonstrated effectiveness of LoRA for low-resource LLM adaptation
- Established a reusable pipeline for future low-resource language experiments

## Applications
- Language preservation and accessibility
- Educational and linguistic research tools
- Foundation for downstream NLP tasks in Tigrinya
