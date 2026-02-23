# 🏆 Tunics Final — Competition-Ready Fine-Tuning with GRPO

A competition-grade Jupyter notebook for fine-tuning **Gemma2-2B-IT** (or Gemma3 1B) using **Tunix + GRPO** (Group Relative Policy Optimization) to produce structured reasoning outputs.

## 🎯 Overview

This notebook is designed to fine-tune a small language model to reliably output structured `<reasoning>...</reasoning>` and `<answer>...</answer>` format, optimized for competition scoring criteria.

## ✨ Key Features

- **GRPO Training** — Uses Group Relative Policy Optimization for reward-based fine-tuning
- - **Structured Output** — Trains model to produce clean reasoning + answer format
  - - **Competition Optimized** — Addresses notebook quality (35pts), model quality (45pts), video (20pts), and optional checkpointing (15pts)
    - - **Reproducible** — Clean, single-session training with loadable checkpoints
      - - **Error-Resistant** — Built for stability during competition runs
       
        - ## 🛠️ Tech Stack
       
        - - **Model**: Gemma2-2B-IT / Gemma3-1B
          - - **Training**: GRPO (Group Relative Policy Optimization)
            - - **Framework**: Tunix / Hugging Face Transformers
              - - **Environment**: Jupyter Notebook
               
                - ## 🚀 Getting Started
               
                - 1. Open the notebook in Kaggle or Google Colab
                  2. 2. Ensure GPU runtime is enabled
                     3. 3. Run all cells sequentially
                        4. 4. Checkpoints are saved automatically for resume capability
                          
                           5. ## 📄 License
                          
                           6. This project is open source and available for educational purposes.
