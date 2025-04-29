# Alcohol-Sleep_Netpyne_model-
This repository contains simulation code and visualizations from a computational neuroscience project investigating the impact of alcohol consumption and sleep deprivation on neuronal activity and memory-related network dynamics.
The project integrates:

🧪 Empirical data from cognitive assessments of university students

🧠 Single-neuron modeling using CompCogNeuro simulations

🧬 Network-level and CA3 hippocampal simulations using NetPyNE

🔍 Goals
Model how alcohol and sleep-related factors affect spiking activity and neural synchrony.

Explore emergent network behaviors (e.g., disinhibition, firing variability) beyond single-cell effects.

Demonstrate how parameter tuning (e.g., synaptic weights, input noise) reflects real-world neurobiology.

📂 Contents
/single_neuron/ – CompCogNeuro-based GE/GL/noise simulations

/microcircuit/ – 100-cell NetPyNE model of E/I interactions

/CA3_model/ – 500-cell CA3 hippocampal model with alcohol adjustments

/plots/ – Spike histograms, raster plots, connectivity matrices

/notebooks/ – Jupyter-ready simulation files with documentation

🧰 Requirements
Python 3.10+

NetPyNE

matplotlib, numpy, Jupyter

📌 Citation
If you use this model or adapt it, please cite:
Amponsah, L.B. (2025). "Exploring the Neural Basis of Alcohol and Sleep Effects on Memory via Multiscale Modeling."
