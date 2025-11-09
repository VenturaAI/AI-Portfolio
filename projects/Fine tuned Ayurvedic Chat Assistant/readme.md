

🧘‍♂️ Ayurgenix — The Ayurvedic Chat Assistant
🌿 Overview

Ayurgenix is an intelligent Ayurvedic chat assistant fine-tuned from DeepSeek-Qwen-1.5B using LoRA adapters.
It provides structured, personalized recommendations for Ayurvedic treatments, herbal remedies, lifestyle improvements, and dosha balancing — based on user-entered symptoms.

Built for healthcare researchers, Ayurveda practitioners, and wellness enthusiasts who want accurate, traditional yet data-driven guidance.

⚙️ Features

🩺 Symptom-based guidance — Understands user-described symptoms and suggests Ayurvedic formulations, Asavas, Avalehas, and home remedies.

🪷 Fine-tuned for Ayurveda — Trained on curated Ayurvedic texts, NCERT-aligned wellness data, and classical herbs information.

🗣️ Conversational — Uses DeepSeek’s chat-optimized Qwen architecture for fluent and contextual dialogue.

⚡ Lightweight & Quantized — Runs in 4-bit precision (NF4) for fast inference on consumer GPUs.

💬 Integrated UI — Gradio-based chat interface for interactive usage.

🧩 Model Architecture
Component	Details
Base Model:	deepseek-ai/DeepSeek-R1-Distill-Qwen-1.5B
Fine-Tuning:	LoRA (Low-Rank Adaptation)
Quantization:	4-bit NF4 (BitsAndBytesConfig)
Frameworks:	PyTorch, Transformers, PEFT, Gradio
Tokenizer Source	Adapter directory (custom chat_template.jinja)

<img width="1920" height="1080" alt="Screenshot (51)" src="https://github.com/user-attachments/assets/64fee768-c4bd-4247-b6f9-8bc9de5dd2ed" />
