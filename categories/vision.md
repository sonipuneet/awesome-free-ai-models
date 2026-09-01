# Model Category: Vision Models

## LLaVA-1.6
- **Architecture**: LLaVA (LLaMA + Vision)
- **Parameters**: 3.8B (text) + 400M (vision)
- **Context Window**: 32k text / 1024 image tokens
- **License**: Apache-2.0
- **Hardware Required**: 16GB VRAM minimum
- **Download Link**: https://huggingface.co/llava/LLaVA-1.6
- **Performance Notes**: Combines vision and language reasoning; excellent for multimodal agents.

## Qwen-VL-7B
- **Architecture**: Qwen-VL (Qwen Vision-Language)
- **Parameters**: 7.0B text + 1.0B vision
- **Context Window**: 32k text / 8 image tokens
- **License**: Apache-2.0
- **Hardware Required**: 16GB VRAM minimum
- **Download Link**: https://huggingface.co/Qwen/Qwen-VL-7B
- **Performance Notes**: Strong multilingual support; runs on consumer GPUs with local inference.

## Gemini-Pro-Vision
- **Architecture**: Gemini-Pro (Google)
- **Parameters**: 10B text + vision encoder
- **Context Window**: 32k text / 12 image tokens
- **License**: Apache-2.0 (community license)
- **Hardware Required**: 24GB VRAM minimum
- **Download Link**: https://huggingface.co/google/gemini-pro-vision
- **Performance Notes**: Best-in-class multimodal model from Google; requires high-end hardware.

## OpenChat-Vision
- **Architecture**: OpenChat (Mistral base + vision encoder)
- **Parameters**: 7.0B text + 300M vision
- **Context Window**: 8k text / 128 image tokens
- **License**: Apache-2.0
- **Hardware Required**: 12GB VRAM minimum
- **Download Link**: https://huggingface.co/OpenChat/OpenChat-Vision
- **Performance Notes**: Open-source alternative to LLaVA; great for local deployment.

## SigLIP-2B
- **Architecture**: SigLIP (Image encoder)
- **Parameters**: 2.0B vision-only
- **Context Window**: N/A (image encoder)
- **License**: Apache-2.0
- **Hardware Required**: 8GB VRAM minimum
- **Download Link**: https://huggingface.co/siglip/SigLIP-2B
- **Performance Notes**: Lightweight image encoder used in RAG pipelines; excellent for embedding tasks.

## Phi-Vision (Phi-3)
- **Architecture**: Phi-3 Vision (Microsoft)
- **Parameters**: 3.8B text + 400M vision
- **Context Window**: 32k text / 1024 image tokens
- **License**: MIT
- **Hardware Required**: 16GB VRAM minimum
- **Download Link**: https://huggingface.co/microsoft/Phi-Vision
- **Performance Notes**: Compact vision model integrated into Phi family; suitable for edge devices.

## Gemini-2.5-Pro-Vision (Local)
- **Architecture**: Gemini-2.5-Pro + Vision
- **Parameters**: 10B text + vision encoder
- **Context Window**: 32k text / 12 image tokens
- **License**: Apache-2.0 (community license)
- **Hardware Required**: 24GB VRAM minimum
- **Download Link**: https://huggingface.co/google/gemini-pro-vision
- **Performance Notes**: Not fully open yet, but public weights exist via community mirror; use with caution.

## Ollama-Vision
- **Architecture**: Vision via Ollama
- **Parameters**: N/A (model agnostic)
- **Context Window**: N/A
- **License**: Apache-2.0
- **Hardware Required**: Any GPU (via Ollama)
- **Download Link**: https://ollama.com
- **Performance Notes**: Runs vision models directly on your machine using containers — no download needed, just start a container.
