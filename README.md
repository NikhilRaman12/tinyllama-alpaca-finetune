# TinyLlama Alpaca Finetune Project

This project contains code for finetuning the TinyLlama-1.1B-Chat-v1.0 model on the Alpaca dataset using QLoRA in Google Colab.

## HuggingFace Model:
[NikhilRaman1203/tinyllama-alpaca-instruct-v1](https://huggingface.co/NikhilRaman1203/tinyllama-alpaca-instruct-v1)

## Project Structure:
- `this_notebook.ipynb`: The Colab notebook containing the finetuning code.
- `qlora-output/`: Directory where the finetuned LoRA adapters are saved.
- `requirements.txt`: List of Python dependencies.

## Setup and Usage:
1. Open this notebook in Google Colab.
2. Run all cells to install dependencies, load the model and dataset, perform finetuning, and evaluate the model.
3. The finetuned model can be tested locally and pushed to HuggingFace Hub.

## Libraries Used:
- `transformers`
- `datasets`
- `trl`
- `peft`
- `bitsandbytes`
- `accelerate`
- `evaluate`

