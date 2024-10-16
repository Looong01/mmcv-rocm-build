# mmcv-rocm-build
ROCm build of MMCV

# How to use
1. Be sure that you have installed ROCm 6.1 or newer versions. You can use ```rocm-smi``` to check it.
2. Go to Releases module, choose the versions of MMCV you want and the right version of your Python environment.
3. Download the wheel(.whl) file.
4. ```pip install ./*.whl```
  
# Build environment
```
Ubuntu 22.04
PyTorch 2.4.1 for Python 3.8~3.12
ROCm 6.1.3~6.2.3
```
  
# Current version
```
mmcv-2.2.0
```