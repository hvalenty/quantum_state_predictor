# quantum_state_predictor
Project as part of PHYS474 (Quantum Mechanics I) at Duquesne University


# Quantum State Predictor
This course was taught by Dr. Theodore Corcovilos @corcoted, who presented the class with the Quantum Guessing Game. The game utilized the computer picking a random quantum spin-1/2 state from a predetermined list. The players (student teams) request measurements in the form of the Pauli operators Sx, Sy, or Sz and attempt to guess the state. But before the game, more on quantum properties.

# Quantum Spin States

## Quantum State
Generally, a state is what condition a system is in at a specific point in time. States are mathematical representations used in explanation of an object. For example, in classical mechanics the position and velocity vectors are mathematical entities dedscribing the motion of an object in question. Quantum mechanics has a parallel to this descriptive format using bra-ket vectors. These pieces of notation do not convey the same physical representation that the position and velocity vectors do, rather they model the knowledge of a quantum system/particle. 


## Spin
Spin is an intrinsic property of all fundamental particles, with this project focused on spin-1/2 particles known as fermions. Fermions are the particles which build the matter of the universe, as opposed to bosons which have integer spin and are the force carriers. Examples of fermions include the proton, neutron, and electron among others. 

Spin is also referred to as the spin angular momentum quantum number, and is quantized using the reduced Planck constant h/2pi (h-bar). This number can be either positive or negative 1/2 for our particles of interest. 

## Spin-1/2 Quantum States
Just as a position vector in Cartesian 3-dimensional space can be written as components of the x, y, and z positions; similar methods are used for describing the state of a spin-1/2 particle. Quantum state vectors can be written in terms of the components of positive and negative spin, with a column vector in the form of (+, -). So, a positive spin-1/2 particle would have a vector representation of (1, 0), where the negative spin-1/2 is represented by (0, 1). For example, a state vector can be written as the linear combination seen as: $ \frac{1}{\sqrt{5}}(1, 0) + \frac{2}{\sqrt{5}}(0,1) $. 

# Rules of the Game
