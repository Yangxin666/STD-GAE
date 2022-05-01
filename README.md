# Spatio-Temporal Denoising Graph Autoencoder (STD-GAE)

This repository contains the code for the reproducibility of the experiments presented in the paper "Spatio-Temporal Denoising Graph Autoencoders with Data Augmentation for Photovoltaics (PV) Data Imputation". In this paper, we propose a novel Spatio-Temporal Denoising Graph Autoencoder (STD-GAE) framework for PV timeseries data imputation and achieve state-of-the-art results on real-world PV benchmarks.


<h2 align=Left>STD-GAE in a nutshell</h2>

Our paper introduces __STD-GAE__, a method and an architecture that exploits temporal correlation, spatial coherence, and value dependencies from domain knowledge to recover missing data. STD-GAE features domain-knowledge aware data augmentation module and data corruption to create plausible variations of missing data patterns (configurable missing data masks). To improve the accuracy of imputation accuracy at PV fleet level, STD-GAE integrates spatiotemporal graph convolution layers (to recover local missing data by observed “neighboring” PV plants) and denoising autoencoder (to recover corrupted data from augmented counterpart).

<img src="./STD-GAE.png" alt="Logo"/>


