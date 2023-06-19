Title: Rocket Payload Balancing with Grover Search
Date: 2023-06-14 21:19
Category: Quantum Computing
Tags: Quantum Computing, Grover Search, Quantum Arithmetic, Discrete Optimization
Author: dln-dev
Summary: The fuel consumption of rockets grows exponentially with payload mass. Balancing the payload distribution among two (and probably more) rockets can be done using Grover search. Constructing the oracle is not straightforward. 

# Rocket Payload Balancing with Grover Search

* rocket equation quick derivation
* show exponential fuel consumption with payload mass
* hence, interesting to balance payloads among rockets
* here, two rockets


## Problem Formulation

* Payload distribution as binary string, 010101 means every even-indexed weight goes to rocket 1, every other weight to rocket 0 -> first register
* second register holds binary string corresponding to total weight of payload in rocket 1, entangled with distributions, how?
* controlled Fourier rotations


## Grover Search

* explain roughly, Householder mechanism?
* idea: oracle marks every state corresponding to half the total payload weight
* show oracle construction


## Results
* show simulator
* show simulator with calibrated noise
* show real results on IBM hardware


## Conclusion
* summary
* ways to generalize?
* Is this sensible? Mentiond alternating mass distribution from high to low
