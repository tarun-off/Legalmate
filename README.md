⚖️ LegalMate – Domain-Specific LLM Finetuning for Legal Q&A
LegalMate is a fine-tuned open-source LLM designed to specialize in answering India-based legal queries, particularly related to topics such as IPC, CrPC, Contract Law, and more. This project demonstrates the practical impact of LoRA-based finetuning on a base model like Mistral, making it more domain-aware, accurate, and relevant in a specific use case.

🔍 What It Does
Improves Legal Understanding
Fine-tunes the Mistral LLM on curated legal Q&A data using QLoRA, enhancing the model’s ability to generate more accurate, jurisdiction-specific answers.

Contextual Q&A Accuracy
Compares baseline model performance vs fine-tuned performance on structured prompts to show improvements in relevance, tone, and accuracy.

Low-Cost Finetuning
Utilizes QLoRA (Quantized LoRA) to reduce GPU memory usage, allowing training on a Google Colab free tier GPU (T4) with minimal compute resources.

🏗️ Project Architecture
Base Model: Mistral-7B (hosted locally using LM Studio / Ollama)

Finetuning Method: QLoRA using Huggingface’s peft + transformers

Training Environment: Google Colab with T4 GPU

Dataset: Custom-annotated Indian legal Q&A pairs across IPC, CrPC, Contract Law

Evaluation: Prompt-based evaluation comparing original and fine-tuned outputs

🔧 Tech Stack
LLM Frameworks: Huggingface Transformers, PEFT, Bitsandbytes, Datasets

Finetuning Strategy: LoRA / QLoRA

Notebook Runtime: Google Colab (Free Tier)

Serving Models: LM Studio / Ollama for offline inference

Model Compression: 4-bit quantization (QLoRA) for lightweight finetuning

🚀 Why This Project?
Fine-tuning is critical for making open-source models useful in specific domains like law, healthcare, or finance. This project demonstrates:

How open-source models can be trained with minimal compute

How domain-specific datasets can drastically improve response quality

How LoRA and QLoRA make model training accessible and affordable
