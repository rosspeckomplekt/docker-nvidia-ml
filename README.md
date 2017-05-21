# Docker image for machine learning on GPU

## Installed packages

- scikit-learn
- numpy
- scipy
- pandas
- awscli
- click
- tkdm
- PyTorch

## Usage example on AWS

First, create GPU instance on AWS and ssh to the remote machine.
See official wiki: [Deploy on Amazon EC2](https://github.com/NVIDIA/nvidia-docker/wiki/Deploy-on-Amazon-EC2).

Then, on the remote machine try

```
$ nvidia-docker run --rm -it nvidia/cuda python
>>> import numpy as np
```
