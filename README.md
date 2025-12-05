# HKUST MATH5470 final project
## Benchmarking Machine learning Super-Resolution Models for Climate Downscaling

## Overview

  This study investigates the performance of various deep learning models, including UNet-family architectures, Swin Transformer, and ViT variants, in generating high-resolution wind speed data from low-resolution inputs. Our findings reveal that UNet-family models consistently outperform other architectures across diverse evaluation subsets, demonstrating their superior ability to preserve high-resolution spatial information essential for accurate wind-field reconstruction, a strength attributed to their architectural design, particularly the use of skip connections. In contrast, transformer-based models, especially ViT variants, show significant performance degradation. This decline is largely due to their early patchification process, which discards fine-scale information critical for accurately reconstructing high-resolution wind structures. Moreover, extreme-weather evaluation reveals amplified performance divergence across model architectures. This research highlights the importance of architectural design in meteorological downscaling tasks and provides valuable insights into the effectiveness of various super-resolution techniques for enhancing wind speed data accuracy, especially under extreme weather conditions.



## Jupyter Notebooks

We provide Jupyter Notebooks of the downscaling model code, in the downscaling_model_code_jupyter.zip


## Dataset

We have open-sourced all the data required for training and testing deep learning models, which can be downloaded through the following link.

https://pan.baidu.com/s/16lNVA6kMjlq2nECq3oM4rg?pwd=tktp

