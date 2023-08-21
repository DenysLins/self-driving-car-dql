# Self-Driving Car Project with Deep Q-Learning

Welcome to the GitHub repository for our Self-Driving Car Project! This project aims to simulate and demonstrate the capabilities of an autonomous vehicle using Deep Q-Learning combined with popular Python libraries like Numpy, Matplotlib, Kivy, and Torch.

## Table of Contents

- [Self-Driving Car Project with Deep Q-Learning](#self-driving-car-project-with-deep-q-learning)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Prerequisites](#prerequisites)
  - [Installation \& Setup](#installation--setup)
  - [How to Use](#how-to-use)
    - [Training with Deep Q-Learning](#training-with-deep-q-learning)
  - [Documentation](#documentation)
  - [License](#license)
  - [Contact](#contact)

## Introduction

In this project, we leverage the power of Deep Q-Learning, a model-free, online, off-policy reinforcement learning method, to train our self-driving car. Deep Q-Learning combines the generalization capabilities of deep neural networks with the power of Q-Learning, allowing our autonomous vehicle to make more informed decisions based on its environment.

## Prerequisites

- **Python:** We recommend using Python 3.8 or above.
- **Libraries:** This project heavily relies on the following Python libraries:
  - Numpy
  - Matplotlib
  - Kivy
  - Torch

## Installation & Setup

1. **Clone the Repository:**

```bash
git clone https://github.com/DenysLins/self-driving-car-dql.git

cd self-driving-car-dql
```

2. **Create a Virtual Environment (Optional, but Recommended):**

```bash
python -m venv venv

source venv/bin/activate
```

3. **Install Required Packages:**

```bash
pip3 install -r requirements.txt
```

## How to Use

### Training with Deep Q-Learning

1. **Setup the Environment:** Make sure the car simulator is active.
2. **Run the Training Script:** `python dqn_training.py`
3. **Monitor Progress:** You can visualize the car's learning progress using Matplotlib. The plot will show rewards over time, a key indicator of how well the car is learning to drive.

## Documentation

**Deep Q-Learning Implementation Details:** Deep Q-Learning uses a neural network, implemented in Torch, to approximate the Q-values. The network takes the state of our simulated environment as input and outputs Q-values for each action. During training, the car learns to update these Q-values based on rewards it receives from the environment, thus improving its driving strategy.

## License

This project is licensed under the MIT License. See [LICENSE](./LICENSE) for more details.

## Contact

Denys Lins - [Email](mailto:denyslins@gmail.com) - Twitter: [@Denys_Lins](https://twitter.com/Denys_Lins)
