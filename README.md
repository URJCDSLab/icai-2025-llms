# icai-2025-llms


## Installation

### Python libraries

### Install libraries
```bash
pip install transformers==4.53.1
pip install torch==2.7.1
```

### Download Models
```bash
huggingface-cli download gpt2
huggingface-cli download distilbert-base-uncased-finetuned-sst-2-english
```

### Ollama

#### Install Ollama
Download from [ollama.com/download](https://ollama.com/download)

#### Download Models
```bash
ollama pull llama3:instruct
ollama pull deepseek-r1:8b
ollama pull llama3:text
```