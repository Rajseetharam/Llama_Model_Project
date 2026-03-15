# Llama_Model_Project
A high-performance chatbot interface for Llama models, optimized for low-latency local execution and customizable system instructions.
# 🦙 Llama Chatbot (Google colab Notebook)

A high-performance chatbot interface for Llama models, optimized for interactive execution within a Jupyter environment.

## 🚀 Quick Start
1. **Model Access:** Ensure you have requested access to Llama 3 weights on [Hugging Face](https://huggingface.co/meta-llama).
2. **Open Notebook:** Click the "Open in Colab" badge above or download `Chatbot_using_Llama.ipynb`.
3. **GPU Runtime:** In Colab, go to `Runtime > Change runtime type` and select **T4 GPU**.
4. **API Key:** Have your Hugging Face Write Token ready to log in when prompted in the notebook.

## 🛠️ Features
* **Quantized Inference:** Uses 4-bit quantization to fit the model into 16GB VRAM.
* **Interactive UI:** Built-in chat loop directly in the notebook cells.
* **Customizable:** Easy to adjust `temperature` and `max_tokens` for different responses.

## 📦 Requirements
The notebook automatically installs:
* `transformers`
* `bitsandbytes` (for quantization)
* `accelerate`
