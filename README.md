# Taxi-v3 — Value Iteration & Reinforcement Learning

Third project for **Introduction to AI** (Amirkabir University of Technology).

Implements solution methods for OpenAI Gymnasium’s **Taxi-v3** environment in a Jupyter notebook, including value iteration and policy extraction, with optional video recording of the learned policy.

## Contents

| File | Description |
|------|-------------|
| `taxi_gym.ipynb` | Main notebook (Taxi env, value iteration, evaluation) |
| `requirements.txt` | Python dependencies |
| `report.pdf` | Project report |

## Setup

```bash
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## Run

```bash
jupyter notebook taxi_gym.ipynb
```

Or open the notebook in VS Code / JupyterLab and run all cells.

## Topics covered

- Taxi-v3 MDP (states, actions, rewards)
- Value iteration
- Optimal policy extraction
- Policy evaluation / recorded rollouts

## Requirements

- Python 3.9+
- `gymnasium`, `numpy`, Jupyter stack (see `requirements.txt`)
