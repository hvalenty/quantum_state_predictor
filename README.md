# quantum_state_predictor
Project as part of PHYS474 (Quantum Mechanics I) at Duquesne University


## Quantum State Predictor
This course was taught by Dr. Theodore Corcovilos `@corcoted`, who presented the class with the Quantum State Guessing Game. The game utilized the computer picking a random quantum spin-1/2 state from a predetermined list. The players (student teams) request measurements in the form of the Pauli operators Sx, Sy, or Sz and attempt to guess the state. 

## Our Task
Ultimately, our team (Rebecca Nelson, Duq '22 and myself) had to develop an algorithm to get the best possible score in the game, and especially beat the other team. The algorithm is a deterministic set of rules that could only take spectific inputs, while producing the outputs:

*   Which direction of measurement to request
*   When to guess and what state to guess

## Methods

The `quantum_state_predictor` notebook outlines the process we took to win the quantum state guessing game. Our (successful) method came in the form of Bayesian estimation with updating. 

Having the goal to minimize the sample size and desiring the best guess possible lead us to Bayesian estimation. 

Bayes theorem is infinitely useful to make distributed estimations and guide us to lean on guess probabilities. 

## Results
We won! Our team was the victor.