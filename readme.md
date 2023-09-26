# Metropolis Algorithm in a Hopefield Network

## Introduction

Neural network following Hopfield's model.
Bidemensional matrix formed by $N\times N$ neurons ( $s_{i,j}$ is the nueron in position $(i,j)$ )  with the following carateristics:

1.  Neurons are binary. Two possible states: 0, inactive; 1, active.
2.  The interaction of $s_{i,j}$ with $s_{k,l}$ is defined $w_{i,j,k,l}$ ('Learned' via Hebb's Law of association). Each neuron interacts with every other one except with itself ( $w_{i,i} = 0$ ). 
3.  The interaction is symetric: $w_{i,j} = w_{j,i}$
