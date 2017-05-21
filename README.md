# Docker image for machine learning on GPU

## Installed packages

- scikit-learn
- numpy
- scipy
- pandas
- awscli
- click
- tqdm
- torch

## Usage example on AWS

First, create GPU instance on AWS and ssh to the remote machine.
See official wiki: [Deploy on Amazon EC2](https://github.com/NVIDIA/nvidia-docker/wiki/Deploy-on-Amazon-EC2).

Then, on the remote machine try

```
$ nvidia-docker run --rm -it sotetsuk/nvidia-ml python
Python 3.6.0 |Continuum Analytics, Inc.| (default, Dec 23 2016, 12:22:00)
[GCC 4.4.7 20120313 (Red Hat 4.4.7-1)] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> import numpy as np
```
