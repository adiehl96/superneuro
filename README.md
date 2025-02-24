# SuperNeuro
Neuromorphic simulator with two modes of computation:

1. Agent Based Mode (ABM) - SuperNeuroABM
2. Matrix  Computation - SuperNeuroMAT

## Installation: SuperNeuroABM

**Requirements:**

Python version >=3.8

**Optional requirements if running on GPU:**

CUDA enabled GPU with compute compatibility 6.0+

CUDA drivers

`pip install superneuroabm`

Or if the above doesn't work, you can try this:

`pip install git+https://github.com/ORNL/superneuroabm`

### Usage: 
`from superneuroabm.model import NeuromorphicModel`

SuperNeuroABM allows one to run simulations on GPUs. It can be accessed by instantiating the model as 

`NeuromorphicModel(use_cuda = True)`


## Intstallation: SuperNeuroMAT

Requirements: Python version >=3.8

`pip install superneuromat`

Or if the above doesn't work try the following from the github repo:

`pip install git+https://github.com/ORNL/superneuromat.git`

### Usage:

`from superneuromat.neuromorphicmodel import NeuromorphicModel`

In each of the modes, the neuromorphicmodel allows the user to create neurons and synapses as per the application or algorithm requirements.

## Tutorials:
Jupyter notebooks with tutorials for each of the two modes of SuperNeuro are located in the 'Tutorials' directory.
