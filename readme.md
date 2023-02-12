# just xformers builder on github action
inspired from https://github.com/ninele7/xfromers_builds/blob/main/.github/workflows/build.yml and from https://github.com/facebookresearch/xformers/blob/main/.github/workflows/wheels.yml

# list cuda version
https://en.m.wikipedia.org/wiki/CUDA#GPUs_supported

# default TORCH_CUDA_ARCH_LIST
5.0;5.2+PTX;5.3;6.0;6.1+PTX;7.0+PTX;7.5+PTX;8.0;8.6+PTX

# colab TORCH_CUDA_ARCH_LIST
7.0+PTX;7.5+PTX;8.0;8.6+PTX