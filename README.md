# Hyperpose - Amper Architecture
> Hyperpose built with CUDA11.3.1 and CuDNN8.
 
> compatible with the Amper Architecture: RTX 3090 / Jetson AGX ORIN.
 
> Instructions provided to modify the source code and enable training with Amper Architecture and CUDA11.

Hyperpose is a machine learning development framework that leverages the power of Tensorflow and TensorRT for deployment.
It is relatively easy to use and well documented here:  https://hyperpose.readthedocs.io/en/latest/ 



# Docker image 
- can be pulled from the docker repo `elio99/hyperpose` with:
```bash
$ docker pull elio99/hyperpose:cuda11.3
```

# Python Installation & Model Training

> To train a model with the newer Amper Architecture GPUs, check the README.md in the Python folder.

# Format Convertion to ONNX for Deployment

> Check the README.md in the ONNX Convertion folder.
