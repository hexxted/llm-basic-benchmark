# LLM Basic Benchmark 🧠📊

![GitHub release](https://img.shields.io/badge/releases-latest-brightgreen?style=flat-square&logo=github)

Welcome to the **LLM Basic Benchmark** repository! This project provides a comprehensive benchmark of 44 open-source language models. We evaluate these models across various tasks, including creative writing, logic puzzles, counterfactual reasoning, and programming challenges. This benchmarking suite is tested on the Apple M4 Max, ensuring detailed performance analysis and insights.

## Table of Contents

- [Introduction](#introduction)
- [Models Included](#models-included)
- [Benchmarking Tasks](#benchmarking-tasks)
- [Performance Analysis](#performance-analysis)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Introduction

In today's world, language models are becoming increasingly important in various applications. From generating creative content to solving complex problems, these models showcase remarkable capabilities. This benchmark aims to provide a clear comparison of different models, helping researchers and developers make informed decisions.

For the latest releases, check out our [Releases section](https://github.com/hexxted/llm-basic-benchmark/releases).

## Models Included

This benchmark evaluates the following language models:

- **Cogito**
- **Gemma3**
- **Granite3**
- **Llama3**
- **Llama4**
- **Phi4**
- **Qwen3**
- **Ollama**
- **MLX**

Each model has unique strengths and weaknesses, which we explore in detail.

## Benchmarking Tasks

We assess the models across four primary tasks:

### Creative Writing ✍️

This task evaluates the models' ability to generate coherent and engaging narratives. We provide prompts and measure the quality of the output based on creativity, relevance, and fluency.

### Logic Puzzles 🧩

Models tackle a series of logic puzzles. We assess their problem-solving skills and logical reasoning capabilities. This task is crucial for applications in educational tools and game development.

### Counterfactual Reasoning 🔄

In this task, models explore "what if" scenarios. We analyze their ability to generate plausible alternatives and reason through complex situations. This skill is vital for applications in decision-making and storytelling.

### Programming Tasks 💻

Models are tested on their ability to write and debug code. We provide various programming challenges and assess the correctness and efficiency of their solutions. This task is essential for software development and automation.

## Performance Analysis

Our detailed performance analysis provides insights into each model's strengths and weaknesses. We present data in various formats, including tables and graphs, to make comparisons easy to understand. The analysis covers:

- **Accuracy**: How well the models perform on each task.
- **Speed**: The time taken to generate responses.
- **Resource Usage**: Memory and CPU consumption during benchmarking.

This information helps users select the right model for their specific needs.

## Installation

To get started with the LLM Basic Benchmark, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/hexxted/llm-basic-benchmark.git
   cd llm-basic-benchmark
   ```

2. **Install Dependencies**:
   Make sure you have Python 3.8 or higher installed. Use pip to install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Download Models**:
   Follow the instructions in the `models` directory to download the language models you wish to benchmark.

## Usage

Once you have set up the repository, you can start benchmarking the models. Use the following command to run the benchmark:

```bash
python benchmark.py --model <model_name> --task <task_name>
```

Replace `<model_name>` with the name of the model you want to test and `<task_name>` with the task you wish to evaluate. 

For example, to test the Llama3 model on creative writing:

```bash
python benchmark.py --model llama3 --task creative_writing
```

You can find more details about the command-line options in the `docs` folder.

## Contributing

We welcome contributions to enhance this benchmark. If you want to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with clear messages.
4. Push your branch to your forked repository.
5. Open a pull request.

Please ensure your code follows our coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

We thank the developers and researchers behind the open-source language models we benchmark. Your work drives innovation and progress in the field of natural language processing.

For the latest releases, check out our [Releases section](https://github.com/hexxted/llm-basic-benchmark/releases). 

Explore, benchmark, and enjoy!