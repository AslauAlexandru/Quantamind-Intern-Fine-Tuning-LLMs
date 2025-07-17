# Quantamind Intern Fine-Tuning LLMs
You can run from Google Colab here: [Quantamind_Intern_Fine_Tuning_LLMs.ipynb](https://colab.research.google.com/drive/1viDzLJ1wQOq7FWUoa-D6kwl2jheB4vYV?usp=sharing).

## Project description
Fine-Tuning Llama 3.2 for text generation using two datasets and different methods.
Fine-Tuning Llama 3.2 model for text generation using QLoRa method and Supervised Fine-tuning Trainer (SFT) method with [Maxime Labonne's FineTome-100k dataset](https://huggingface.co/datasets/mlabonne/FineTome-100k) in ShareGPT style and inference method, other approach using QLoRa method and GRPO Trainer method with [OpenAI's famous GSM8K dataset](https://huggingface.co/datasets/openai/gsm8k) and inference method.


## Model & dataset used

Model used: Llama-3.2-1B-Instruct from [unsloth ai](https://unsloth.ai/) (``` model_name = "unsloth/Llama-3.2-1B-Instruct" ```).

[Maxime Labonne's FineTome-100k dataset](https://huggingface.co/datasets/mlabonne/FineTome-100k) in ShareGPT style used for QLoRa method and Supervised Fine-tuning Trainer (SFT) method, the FineTome dataset is a subset of [arcee-ai/The-Tome](https://huggingface.co/datasets/arcee-ai/The-Tome) (without arcee-ai/qwen2-72b-magpie-en), re-filtered using [HuggingFaceFW/fineweb-edu-classifier](https://huggingface.co/HuggingFaceFW/fineweb-edu-classifier).The Tome [arcee-ai/The-Tome](https://huggingface.co/datasets/arcee-ai/The-Tome) (without arcee-ai/qwen2-72b-magpie-en) is a curated dataset designed for training large language models with a focus on instruction following. It was used in the training of our Arcee-Nova/Spark models, which was later merged with Qwen2-72B-Instruct (or 7B with the Spark model).


[OpenAI's famous GSM8K dataset](https://huggingface.co/datasets/openai/gsm8k): Dataset Card for GSM8K. Dataset Summary.
GSM8K (Grade School Math 8K) is a dataset of 8.5K high quality linguistically diverse grade school math word problems. The dataset was created to support the task of question answering on basic mathematical problems that require multi-step reasoning.

- These problems take between 2 and 8 steps to solve.
- Solutions primarily involve performing a sequence of elementary calculations using basic arithmetic operations (+ − ×÷) to reach the final answer.
- A bright middle school student should be able to solve every problem: from the paper, "Problems require no concepts beyond the level of early Algebra, and the vast majority of problems can be solved without explicitly defining a variable."
- Solutions are provided in natural language, as opposed to pure math expressions. From the paper: "We believe this is the most generally useful data format, and we expect it to shed light on the properties of large language models’ internal monologues""

Dataset Structure: ``` {
    'question': 'Natalia sold clips to 48 of her friends in April, and then she sold half as many clips in May. How many clips did Natalia sell altogether in April and May?',
    
    'answer': 'Natalia sold 48/2 = <<48/2=24>>24 clips in May.\nNatalia sold 48+24 = <<48+24=72>>72 clips altogether in April and May.\n#### 72',
} ```


## Explanation of both methods



## Steps to run the code


## Results and performance comparison





## Final conclusion and recommendation




