# [Video guide of installing CPU and GPU TensorFlow on Windows](https://www.youtube.com/watch?time_continue=5&v=r7-WPbx8VuY) 

# My System info
- CPU: Intel(R) Core(TM) i5-4590 CPU @ 3.30GHz  3.30GHz
- GPU: NVIDIA GeForce GTX 960
- OS: Microsoft Windows 10 Pro 64-bit
- OS Version: 10.0.14393 N/A Build 14393

# Installation Steps:

## Check if your NVIDIA GPU is [supported](https://developer.nvidia.com/cuda-gpus) for Tensorflow:
GeForce GTX 960 Compute Capability: 5.2     

## [Python 64-bit](https://www.python.org/downloads/) installation

### To install the CPU-only version of TensorFlow, enter the following command at a Windows command prompt:
```python
pip install --upgrade https://storage.googleapis.com/tensorflow/windows/cpu/tensorflow-0.12.1-cp35-cp35m-win_amd64.whl
```  
      
### To install the GPU version of TensorFlow, enter the following command at a command prompt:
```python
pip install --upgrade https://storage.googleapis.com/tensorflow/windows/gpu/tensorflow_gpu-0.12.1-cp35-cp35m-win_amd64.whl
```

## [CUDA installation](https://developer.nvidia.com/cuda-downloads)

## [cudnn](https://developer.nvidia.com/rdp/cudnn-archive)
[cuDNN v5 Library for Windows 10](https://developer.nvidia.com/rdp/assets/cudnn-8.0-windows10-x64-v5.0-ga-zip)

## Verify if tensorflow-gpu version is installed or not in python command prompt:
```python
import tensorflow
I c:\tf_jenkins\home\workspace\release-win\device\gpu\os\windows\tensorflow\stream_executor\dso_loader.cc:128] successfully opened CUDA library cublas64_80.dll locally
I c:\tf_jenkins\home\workspace\release-win\device\gpu\os\windows\tensorflow\stream_executor\dso_loader.cc:128] successfully opened CUDA library cudnn64_5.dll locally
I c:\tf_jenkins\home\workspace\release-win\device\gpu\os\windows\tensorflow\stream_executor\dso_loader.cc:128] successfully opened CUDA library cufft64_80.dll locally
I c:\tf_jenkins\home\workspace\release-win\device\gpu\os\windows\tensorflow\stream_executor\dso_loader.cc:128] successfully opened CUDA library nvcuda.dll locally
I c:\tf_jenkins\home\workspace\release-win\device\gpu\os\windows\tensorflow\stream_executor\dso_loader.cc:128] successfully opened CUDA library curand64_80.dll locally
``` 
Done!

 
