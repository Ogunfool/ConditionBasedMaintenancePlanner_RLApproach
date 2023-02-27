# Condition-based Maintenance Planner: A Reinforcement Learning Approach.
It contains a python-based survival analysis model to study the lifetime of machines in a 3-unit flowline production system, The simulation environment to be used with the RL algorithm for maintenance planning, Q-learning algorithm based maintenance policy, corrective and preventive maintenance policy simulations for comparison.
In this project, a reinforcement learning approach is used to develop a condition-based maintenance
policy for a three-unit serial production line with individually repairable machines, each machine has
separate degradation path and failure rates. Survival analysis is used to model and study the lifetime
of the machines, the Weibull distribution is used to describe the observed system failures and fit the
survival function to the dataset. The machine’s ages are discretized using predefined thresholds to
get their degradation levels and a combination of the machine degradation levels is used to define the
observable states. The optimal maintenance action for each component at each state is found by modelling
the problem as a Markov decision process and solving it with the Q-learning algorithm. Finally,
to evaluate the performance of the proposed policy, it is compared to two (2) baseline maintenance
policies, the corrective and periodic maintenance policies in terms of the average maintenance costs
and frequency of machine failures.
