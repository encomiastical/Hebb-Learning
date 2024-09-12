# Hebb-Learning
My final project for the course "Neurodynamics" in SS2023. Project is still pending for review for publication in Student Journal

In this project, I implement Hebb Learning using a Brian2 implementation of Gerstner's model of a NMDA Synapse. I create a system of differential equations which are equivalent to the integrated form given in Gerstner's book. Proof of equivalence is in model_proof.pdf. I use the DEs to simulate NMDA Synapses. I control the amount of AMPA Synapses according to the Calcium Hypothesis (manually - this is a bit of cheating but the suggested process is way to involved and poorly understood to model it more explicitly) and show that the resulting System implements Hebb Learning.
