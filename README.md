# LP Optimization and Integration

Two Python scripts: a linear programming production optimization problem and a Monte Carlo numerical integration.

## Features

- **task_01.py** — maximizes total product quantity (lemonade + fruit juice) subject to water, sugar, lemon juice, and fruit puree constraints, using `pulp`
- **task_02.py** — estimates the definite integral of `fn(x) = x^2 + 3x - 3` over `[0, 3]` via Monte Carlo sampling (10,000 and 100,000 samples) and compares it to the analytical result from `scipy.integrate.quad`, plotting the function with `matplotlib`

## Technology

- Python 3
- pulp (linear programming)
- numpy, scipy, matplotlib (Monte Carlo integration and plotting)

## Running

```
pip install pulp numpy scipy matplotlib
python task_01.py
python task_02.py
```
