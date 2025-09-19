Biomedical Question Answering with LoRA-Tuned LLMs

This repository contains a Gradio web application for biomedical question answering. The system runs a Mistral-7B base model with a LoRA adapter fine-tuned on biomedical data.
By specializing the foundation model with LoRA, the application provides accurate, domain-aware responses in 2–3 concise paragraphs.

This work aligns with the Bill & Melinda Gates Foundation’s mission to improve global health and equity by making advanced AI tools both accessible and impactful for biomedical research and healthcare.

Features

Biomedical-tuned LLM: Uses a Mistral-7B base model + custom LoRA adapter (emiwang/biomed-lora)

Interactive Web UI powered by Gradio

Concise, paragraph-style answers to biomedical questions

4-bit Quantization (bitsandbytes) for efficient inference on GPUs

Custom Chat Template for structured biomedical outputs
