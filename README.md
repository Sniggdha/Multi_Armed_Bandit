# Multi-Armed Bandit Algorithm
This project implements a multi-armed bandit algorithm to solve the n-armed bandit problem.
The algorithm allows for exploration and exploitation to maximize rewards in a scenario where there are multiple actions (arms) with unknown reward distributions.

## Description
The multi-armed bandit algorithm is a classic problem in the field of reinforcement learning and decision theory.
It involves finding the optimal strategy for choosing actions (arms) over multiple rounds to maximize cumulative rewards.
This implementation considers the scenario where there are n arms with unknown reward distributions.

## Usage
To run the multi-armed bandit algorithm:
1. Clone the repository: git clone https://github.com/Sniggdha/Multi_Armed_Bandit.git
2. Navigate to the project directory: cd Multi_Armed_Bandit
3. Run the Python script: python multi_armed_bandit.ipynb
4. Adjust parameters as needed:
- `num_arms`: Number of arms in the bandit problem (5, 10, or 20).
- `num_steps`: Number of steps to play in each simulation (default: 2000).
- `simulation`: Number of simulations to average out (default: 2000).
- `epsilons`: List of epsilon values for greedy-ness index (e.g., [0.1, 0.01, 0]).

## Results
The algorithm generates two plots to visualize the results:
1. **Average Reward vs Steps**:
- This plot shows the average reward obtained over time for different epsilon values, illustrating the trade-off between exploration and exploitation.

2. **% Optimal Action vs Steps**:
- This plot shows the percentage of optimal actions taken over time for different epsilon values, indicating the algorithm's effectiveness in learning and maximizing rewards.

## Contributing
Contributions are welcome!
If you find any issues, have ideas for improvements, or want to contribute enhancements, feel free to open an issue or submit a pull request.



