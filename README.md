# Asynchronous-Federated-Fourier-Neural-Network-for-Turbulence-Prediction-in-Urban-Air-Mobility-UAM

This repository contains the code for the paper:
- Wireless-Enabled Asynchronous Federated Fourier Neural Network for Turbulence Prediction in Urban Air Mobility (UAM) (https://ieeexplore.ieee.org/abstract/document/10077517)

In this work, to characterize the wireless connectivity performance for UAM, a suitable spatial model is proposed. For the considered setup, assuming that any given aircraft communicates with the closest ground base station (GBS), the distribution of the distance between an arbitrarily selected GBS and its associated aircraft and the Laplace transform of the interference experienced by the GBS are derived. Using these results, the signal-to-interference ratio (SIR)-based connectivity probability is determined to capture the connectivity performance of the UAM aircraft-to-ground communication network. Then, leveraging these connectivity results, a wireless-enabled asynchronous federated learning (AFL) framework that uses a Fourier neural network is proposed to tackle the challenging problem of turbulence prediction during UAM operations. For this AFL scheme, a staleness-aware global aggregation scheme is introduced to expedite the convergence to the optimal turbulence prediction model used by UAM aircraft. Simulation results validate the theoretical derivations for the UAM wireless connectivity. The results also demonstrate that the proposed AFL framework converges to the optimal turbulence prediction model faster than the synchronous federated learning baselines and a staleness-free AFL approach. Furthermore, the results characterize the performance of wireless connectivity and convergence of the aircraft’s turbulence model under different parameter settings, offering useful UAM design guidelines.



## Running environment
- Google Colab with GPU support

## Files
The code is in the form of simple scripts. Each script shall be stand-alone and directly runnable.

- `FNN+AFL.ipynb` is for wireless-enabled asynchronous federated learning (AFL) framework
- `FNN+FL.ipynb` is for orginal federated learning framework

## Datasets
We provide the Burgers equation dataset we used in the paper. 
(https://drive.google.com/file/d/1DWJJkcyrC9mt54FFFbsheLUfm6FA5032/view?usp=sharing)

The datasets are given in the form of matlab file. 

## Cite 
@ARTICLE{10077517,
  author={Zeng, Tengchan and Semiari, Omid and Saad, Walid and Bennis, Mehdi},
  journal={IEEE Transactions on Wireless Communications}, 
  title={Wireless-Enabled Asynchronous Federated Fourier Neural Network for Turbulence Prediction in Urban Air Mobility (UAM)}, 
  year={2023},
  volume={},
  number={},
  pages={1-1},
  doi={10.1109/TWC.2023.3257132}}
