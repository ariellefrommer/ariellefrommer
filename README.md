This repository contains code for simulating neutrino many-body systems without flavor evolution.

kec_states.py creates a momentum lattice and provides a class which, given an initial configuration of neutrinos, will produce the activated states. The other .py files all contain classes for loading in state and momentum data, calculating momentum pairs, calculating the Hamiltonian, and time-evolving a system.

KE_config provides an example usage of all the classes to calculate the Hamiltonian and time-evolve a system, while state_search provides an example of producing activated states. I also put in a sample folder with states and config data.

It also includes a tutorial on dimensionality reduction and data visualization that I wrote for a Harvard course "Astronomy 205: Machine Learning for Astrophysicists."
