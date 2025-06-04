# Reinforcement Learning Benchmark Project

## Project Overview

This project is the final assignment for CSC 594: Deep Generative Models at DePaul University. We implement and analyze various reinforcement learning algorithms on standard benchmark tasks, with a focus on:

- Comparing DQN, PPO, and A2C algorithms on classic control tasks
- Evaluating the impact of reward shaping on learning efficiency
- Testing different neural network architectures for policy/value functions
- Hyperparameter optimization with Optuna
- Experiment tracking with Weights & Biases

## Setup and Installation

```bash
# Create and activate virtual environment
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# Install dependencies
pip install -e .

# For development tools
pip install -e ".[dev]"
```

## Usage

The primary interface is through the RL_Project.ipynb Jupyter notebook, which contains:

- Environment setup and configuration
- Algorithm implementations and comparisons
- Visualization of results
- Hyperparameter tuning experiments

### Selecting the Virtual Environment in VS Code

To use your virtual environment with the notebook in VS Code:

1. Make sure your virtual environment is activated in your terminal:

   ```bash
   # On Windows
   .venv\Scripts\activate
   ```

2. Open the RL_Project.ipynb notebook in VS Code

3. In the top-right corner of the notebook, click on the kernel selector (it might show "Select Kernel" or an existing kernel name)

4. From the dropdown menu, select your .venv Python environment
   - Look for .venv or `Python 3.x (.venv)` in the list

5. Alternatively, you can:
   - Press `Ctrl+Shift+P` to open the command palette
   - Type "Jupyter: Select Notebook Kernel"
   - Choose your .venv environment from the list

6. VS Code will remember this kernel selection for future sessions with this notebook

Now the notebook will use your virtual environment with all the installed dependencies.
