### Prerequisites

* Windows 11(64GB)
* NVidia video card (RTX3060 12GB)
* WSL2 (32GB and operation confirmed on Ubuntu 20.04)

*Not confirmed in other configurations than those listed above.

### Installing

* git clone in the same folder as docker-compose.yaml 

```
git clone https://github.com/Sanster/lama-cleaner.git
```

* Build Docker with the following command
```
docker compose build
```

## Usage

* Access the following after docker compose up -d
```
http://localhost:18080
```

## Version

* 2024/08/12

## Acknowledgments

* [lama-cleaner](https://github.com/Sanster/lama-cleaner) 
* [nVidia 525 + Cuda 11.8 + Python 3.10 + pyTorch GPU Docker image](https://dev.to/ordigital/nvidia-525-cuda-118-python-310-pytorch-gpu-docker-image-1l4a)

