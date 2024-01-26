# Blind Source Seperation
Identify and segment Motor Neurons in EMG signal with Machine Learning

Specifically, we will develop tools to identify the number of sources (number of neurons) in a time series data of biopotentials (High Density Electromyography, HDEMG). This problem is known as Motor Unit Decomposition (MUD), and it will require you to make biologically informed assumptions in designing your heuristics for the decomposition (Blind Source Separation) algorithm. Before we define the actual problem, we will first describe the biological basis of this challenge. Human movements result from electrical activity of neural cells in the central (CNS) and peripheral nervous systems (PNS). The nerve cells directly responsible for innervating the muscles are known as motor neurons. Motor neurons innervate skeletal muscle and cause the muscle contractions that generate movement. The electrical signal generated by motor neurons is known as an action potential and the action potential triggers the contraction of the muscle. The combination of a motor neuron and its innervated muscle fibers is collectively known as the Motor Unit (MU).

![image](https://github.com/ManoharSai2000/blind-source-seperation/assets/45100887/a64e3232-a584-4244-9325-48be9946e246)

This problem is an extension of the cocktail party problem, which involves multiple sound sources and multiple recording microphones. The problem formulation is that we have many sources being mixed (convolved) together with added noise and we have to estimate the inverse of the mixing matrix to recover the individual sources. In case of Motor Unit Decomposition, you have the MUs as sources and HDEMG electrodes as observations. The recording noise and biological tissue act as a mixing matrix. To simplify this problem, we will assume that the sources (MUs) are stationary in space with respect to the recording electrodes.

![image](https://github.com/ManoharSai2000/blind-source-seperation/assets/45100887/a67635c7-0a84-4dd3-809a-d00375dec7f9)


# Project




