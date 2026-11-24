# Solving the Taxi-v3 MDP with Value Iteration

Dynamic-programming solution for Gymnasium’s **Taxi-v3** environment: value iteration, optimal policy extraction, and policy evaluation in a Jupyter notebook.

Built for *Introduction to Artificial Intelligence*, Amirkabir University of Technology (AUT).

**Resume-ready summary:** *Implemented value iteration and optimal policy extraction for the Taxi-v3 MDP in Gymnasium, with recorded policy rollouts.*

## Highlights

- Models Taxi-v3 as a finite MDP (states, actions, transition model, rewards)
- Value iteration to compute the optimal state-value function
- Extracts and evaluates the greedy optimal policy
- Optional video recording of agent behavior

## Contents

| File | Description |
|------|-------------|
| `taxi_gym.ipynb` | Notebook: environment, value iteration, evaluation |
| `requirements.txt` | Python dependencies |
| `report.pdf` | Written project report |

## Tech stack

Python · Gymnasium · NumPy · Jupyter

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

Or open `taxi_gym.ipynb` in VS Code / JupyterLab and run all cells.

## Topics

- Markov Decision Processes (MDPs)
- Bellman optimality equation
- Value iteration
- Policy extraction & evaluation

## Course

Introduction to Artificial Intelligence — Amirkabir University of Technology
