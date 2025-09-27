# Finetuning-Custom-Data-with-Google-Gemma-Model-GenAI-Project
This Repository contains my working files of "Finetuning Custom Data with Google Gemma Model Project", an GenAI Project

(i) Loaded and initialized the pre-trained Gamma-2B model.

(ii) Implemented LoRA (Low-Rank Adaptation) to train only a small subset of model parameters, reducing memory usage and computational cost while fine-tuning multi-billion parameter models.

(iii) Configured optimizer, loss function, and training pipeline in Keras, ensuring stability with selective weight decay and layer exclusions, and performed fine-tuning over the dataset.

(iv) Generated refined, context-aware responses post fine-tuning, demonstrating improved domain-specific performance without retraining the full model, making large LLM adaptation feasible on accessible hardware.
