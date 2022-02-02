# LIMP
### Learning Latent Shape Representations with Metric Preservation Priors

This repository contains the official PyTorch implementation of:

*LIMP: Learning Latent Shape Representations with Metric Preservation Priors.*  
by Luca Cosmo, Antonio Norelli, Oshri Halimi, Ron Kimmel and Emanuele Rodolà.  
Oral at ECCV 2020.  
https://arxiv.org/abs/2003.12283

Please go and cite the original repository if your work is related to it.

The added code to this repository ways used for the AIDA Short Course: Deep Learning for 3D Humans. 
A small demo of the working LIMP method is available in demo_latent.ipynb

## Requirements for LIMP

* tqdm==4.41.1
* numpy==1.18.5
* torch==1.6.0+cu101
* matplotlib==3.2.2
* scipy==1.4.1
* plotly==4.4.1
* requests==2.23.0
* dill==0.3.2
* plyfile==0.7.2
* torch_geometric==1.6.1
* ( torch_scatter==2.0.5) -> not necessary for the demo

## Requirements for the demo (show the 3D shapes in the notebook)

* vtk
* ipyvtklink

## Cite
If you make use of LIMP code in your own work, please cite their paper:
```
@article{cosmo2020limp,
  title={{LIMP: Learning Latent Shape Representations with Metric Preservation Priors}},
  author={Cosmo, Luca and Norelli, Antonio and Halimi, Oshri and Kimmel, Ron and Rodol{\`a}, Emanuele},
  journal={European Conference on Computer Vision (ECCV)},
  year={2020}
}
```

