# Model Category: Fine-Tuning Tools & Libraries

## HuggingFace Transformers
- **Architecture**: HuggingFace Transformers
- **Parameters**: N/A (library)
- **Context Window**: N/A
- **License**: Apache-2.0
- **Hardware Required**: CPU or GPU
- **Download Link**: https://huggingface.co/docs/transformers
- **Performance Notes**: Standard framework for fine-tuning; supports LoRA, full training, and quantization.

## LoRA (Low-Rank Adaptation)
- **Architecture**: LoRA (Parameter-efficient adaptation)
- **Parameters**: 10–100M trainable params
- **Context Window**: N/A
- **License**: Apache-2.0
- **Hardware Required**: CPU/GPU (efficient for small models)
- **Download Link**: https://github.com/DaoCloud/LoRA
- **Performance Notes**: Most popular method for fine-tuning; minimal compute cost; enables adaptation without retraining full models.

## PEFT (Parameter-Efficient Fine-Tuning)
- **Architecture**: PEFT (HuggingFace library)
- **Parameters**: Efficient parameter updates
- **Context Window**: N/A
- **License**: Apache-2.0
- **Hardware Required**: CPU or GPU
- **Download Link**: https://huggingface.co/docs/peft
- **Performance Notes**: Includes LoRA, adapter layers; best for small hardware setups.

## HuggingFace Fine-Tuning API
- **Architecture**: Web-based fine-tuning UI
- **Parameters**: N/A (tool)
- **Context Window**: N/A
- **License**: Apache-2.0
- **Hardware Required**: Browser + internet
- **Download Link**: https://huggingface.co/transformers/fine-tuning
- **Performance Notes**: Allows drag-and-drop fine-tuning without code; great for beginners.

## Text Generation Inference (TGI)
- **Architecture**: TGI Server (Text Generation)
- **Parameters**: N/A
- **Context Window**: N/A
- **License**: Apache-2.0
- **Hardware Required**: GPU server or cluster
- **Download Link**: https://github.com/12britz/text-generation-inference
- **Performance Notes**: Runs models locally with load balancing; ideal for enterprise RAG pipelines.

## Ollama Fine-Tuning
- **Architecture**: Fine-tune via Ollama CLI
- **Parameters**: N/A
- **Context Window**: N/A
- **License**: Apache-2.0
- **Hardware Required**: Any GPU (via Ollama)
- **Download Link**: https://ollama.com
- **Performance Notes**: Simplifies full model training using local containers — no server needed.
