# 📚 ICAI 2025 Workshop: Large Language Models: Generating Text, Generating Threats, Generating Defense

This repository contains all the material from the ICAI 2025 workshop *Large Language Models: Generating Text, Generating Threats, Generating Defense*.


## Installation

### Virtual Environment

It is recommended to create and activate a virtual environment (e.g., conda, venv).

#### Using Conda
```bash
conda create -n icai25 python=3.12
conda activate icai25
```


#### Python Packages
```bash
pip install transformers==4.53.1
pip install torch==2.7.1
```

#### Hugging Face Models
```bash
huggingface-cli download gpt2
huggingface-cli download distilbert-base-uncased-finetuned-sst-2-english
```

### Ollama Setup

#### Install Ollama
Download Ollama for your operation system in [ollama.com/download](https://ollama.com/download)

#### Download Models

```bash
ollama pull llama3:instruct
ollama pull deepseek-r1:8b
ollama pull llama3:text
```


## Notebooks
The demos provided in the slides are also provided in Jupyter Notebooks:

- **Demo 1 - *Exploring How a Decoder Works***: [notebooks/exploring_decoders.ipynb](notebooks/exploring_decoders.ipynb)
- **Demo 2 - *Comparing Pre-trained, Instruct and Reasoning Models***: [notebooks/exploring_models.ipynb](notebooks/exploring_models.ipynb)
- **Demo 3 - *Exploring Prompt Engineering Best Practices***: [notebooks/exploring_prompting.ipynb](notebooks/exploring_prompting.ipynb)
- **Demo 4 - *Exploring Text Generation as a Threat***: [notebooks/exploring_threats.ipynb](notebooks/exploring_threats.ipynb)
- **Demo 5 - *Exploring Text Generation as a Defense***: [notebooks/exploring_defenses.ipynb](notebooks/exploring_defenses.ipynb)