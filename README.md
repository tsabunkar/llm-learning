# Ollama

- This lets you run C++ code
- Run different LLMs locally using Ollama
- Downloading ollama - https://ollama.com/
- Install terminal window
- Open Terminal
- \$ ollama run llama3.2
- Play with Ollama
- Goto Models: https://ollama.com/library/deepseek-r1
- \$ ollama run deepseek-r1
- Choose the model and start playing with

# Data Science Environment

- An Anaconda environment is an isolated collection of software (packages) including libraries and dependencies managed by **Conda** within the broader **Anaconda distribution** for different projects or configurations
- Jupyter is an open-source interactive tool used for creating documents called notebooks where you can write code, add text explanations, and see outputs all in one shared place within a web browser
- Clone the repo: https://github.com/ed-donner/llm_engineering.git
- Install Anaconda Distribution
- \$ conda --version (if doesnt recognize in Zsh, close and reopen the termnial)
- \$ cd llm_engineering
- \$ conda env create -f environment.yml
- \$ conda activate llms (same version of env)
- \$ jupyter lab
