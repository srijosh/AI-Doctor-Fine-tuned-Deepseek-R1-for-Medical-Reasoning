# AI Doctor: Fine-tuned Deepseek R1 for Medical Reasoning

This project demonstrates how to fine-tune the Deepseek R1 model using the Unsloth library on a medical reasoning dataset to build an intelligent AI Doctor assistant. The goal is to create an LLM that can provide medically relevant and reasoning-based responses to healthcare queries.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Results and Evaluation](#results-and-evaluation)
- [Tools and Technologies](#tools-and-technologies)

## Introduction

This AI Doctor project leverages Unsloth for efficient LLM fine-tuning and Deepseek R1 for enhanced reasoning ability in medical conversations. The model is trained on a subset of the medical-o1-reasoning-SFT dataset, optimized to answer patient questions with medical reasoning and context awareness.

## Dataset

- Dataset Source: [FreedomIntelligence/medical-o1-reasoning-SFT](https://huggingface.co/datasets/FreedomIntelligence/medical-o1-reasoning-SFT)

## Features

- Fine-tuned using Unsloth – super-efficient training
- Medical reasoning capabilities with instruction-style Q&A
- Runs efficiently on Colab with 4-bit quantization
- Integrated with Hugging Face Hub and Weights & Biases (WandB)

## Installation

1. Clone the repository to your local machine:

```
   git clone https://github.com/srijosh/AI-Doctor-Fine-tuned-Deepseek-R1-for-Medical-Reasoning.git
```

2. Navigate to the project directory:

```
   cd AI-Doctor-Fine-tuned-Deepseek-R1-for-Medical-Reasoning
```

3. Open Google Colab and Upload AI_Doctor_FineTuned.ipynb for GPU access.

4. Set your Hugging Face Token and WandB Token

## Usage

Run the notebook cells step by step

## Results and Evaluation

- 🧠 The model shows reasonable answers to medical queries after training on only 500 samples

- 📈 Logged all training metrics to WandB

## Tools and Technologies

- 🧠 Deepseek R1

- 🔄 Unsloth

- 📊 W&B

- 🤗 Hugging Face Transformers & Datasets

- ⚙️ Google Colab / Jupyter Notebook
