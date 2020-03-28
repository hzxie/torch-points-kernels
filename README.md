# torch-points
Pytorch kernels for pointnet++ like architectures

## Installation
Requires torch version 1.0 or higher. To install a specific version replace the version number with a given tag.
```
pip install git+https://github.com/nicolas-chaulet/torch-points.git#v0.2.3
```
or with poetry:
```
poetry add git+https://github.com/nicolas-chaulet/torch-points.git#v0.2.3
```

## Usage
```
import torch
import torch_points_kernels.points_cuda
```

## Build and test
```
python setup.py build_ext --inplace
python -m unittest
```

## Projects using those kernels.

[```Pytorch Point Cloud Benchmark```](https://github.com/nicolas-chaulet/deeppointcloud-benchmarks) by
* [Thomas Chaton](https://github.com/tchaton)
* Nicolas Chaulet
* [Tristan Heywood](https://github.com/tristanheywood)

## Credit

* [```Pointnet2_Tensorflow```](https://github.com/charlesq34/pointnet2) by [Charles R. Qi](https://github.com/charlesq34)

* [```Pointnet2_PyTorch```](https://github.com/erikwijmans/Pointnet2_PyTorch) by [Erik Wijmans](https://github.com/erikwijmans)
