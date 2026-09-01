# awesome-free-ai-models

A curated list of **free and open-source** AI models for local execution.  
Designed for developers who want to build powerful AI agents without cloud lock-in or restrictive licenses.

## 🔍 Philosophy

- ✅ **Free**: Open-source licenses (MIT, Apache-2.0, or permissive equivalents).
- ✅ **Local-first**: All models can be run on consumer hardware (GPU/TPU).
- ✅ **Actionable**: Each entry includes architecture, parameter count, context window, hardware requirements, and download links.
- ❌ **Not Hype**: No vague "revolutionary" claims — only verified performance metrics.
- ⚠️ **No Closed-Source Tools**: Excludes platforms requiring API keys or cloud-only access.

## 📚 Structure

Organized by category for clarity:

- `/llms.md` — Large Language Models (e.g., Llama 3, Phi-2)
- `/vision.md` — Vision models (image-to-text, vision-language)
- `/embeddings.md` — Vector databases & text embeddings
- `/multimodal.md` — Models that combine text and vision
- `/fine-tuning.md` — Libraries/tools for training or adapting models

## 🛠️ How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/awesome-free-ai-models.git
   cd awesome-free-ai-models
2. View a model:
    ```# Example: See Phi-2 info
   cat categories/llms.md | grep -A 10 "Phi-2"
3. Run locally:
- Use llama.cpp, Ollama, or Text Generation Inference 
- Most models support quantization (Q4_0, Q5_K) to fit on consumer GPUs   

## TOP 3 
I personally use these locally on a daily basis.

| Model | Platform | Interface | Key Features | Notes |
| --- | --- | --- | --- | --- |
| GPT-oss-20b | LMStudio & anythingLLM | GUI | Strong reasoning, versatile, good for coding tasks | May require significant local resources |
| Qwen3-Coder-30B-A3B-Instruct | llama.cpp | Local API Server | Excellent coding capabilities, efficient quantization | Requires optimized llama.cpp setup |
| Jan-v3.5-4B | Jan LLM | GUI | Lightweight, fast inference, easy to use | Smaller model size but still effective |

## 📄 License

This project is licensed under the MIT License — see [LICENSE](https://github.com/sonipuneet/awesome-free-ai-models/blob/main/LICENSE).

## 📅 Future Roadmap
 - Auto-update from Hugging Face every 3 weeks via GitHub Actions
 - Add benchmark tables for generation quality (e.g., LLaMA vs. Mistral)
 - Include model cards with training data sources (for transparency)

Made with ❤️ by a developer who believe AI should belong to you.

✨ Build responsibly.

Feel free to raise pull requests for any correction / addition / improvements, reviewing weekly.