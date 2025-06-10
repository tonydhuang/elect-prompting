# ELECT Prompting

This is the repository including code and data for our paper - ["Can Large Language Models Be a Good Evaluator for Review-based Product Question Answering?"](https://dl.acm.org/doi/10.1145/3701716.3715586) @ WWW 2025

## Citation

If you used this repository or our method, please cite our work as follows. Thank you!

```
@inproceedings{huang2025can,
  title={Can Large Language Models Be a Good Evaluator for Review-based Product Question Answering?},
  year = {2025},
  author={Huang, Tony Danhui and Ren, Yongli and Zhang, Xiuzhen},
  booktitle={Companion Proceedings of the ACM on Web Conference 2025},
  url = {https://doi.org/10.1145/3701716.3715586},
  doi = {10.1145/3701716.3715586},
  isbn = {9798400713316},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  pages={1019--1023},
  location = {Sydney NSW, Australia},
  series = {WWW '25}
}
```

## Setup

#### 1. Install required packages
To run the code in this repo, you need to install the required packages by running the following command:
```
pip install -r requirements.txt
```

#### 2. Install Ollama

Ollama is a local large language model runner, designed to allow users to download and execute LLMs. Ollama supports many popular large language models, such as multiple versions of Llama, Qwen, Gemma, DeepSeek and other models. Most of our experiments are running locally through Ollama. Please download Ollama from their [offical website](https://ollama.com/download).

#### 3. Versions of LLMs used on our papper
- Llama 3 [on Ollama](https://ollama.com/library/llama3)
- Prometheus 2 [on Ollama](https://ollama.com/tensortemplar/prometheus2:7b-fp16)
- GPT-4o (OpenAI API)
