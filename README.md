#PyTorch implementation of Dynamic Bilinear Fusion Network for Synthetic Aperture Radar Image Change Detection
- **DOI**: [10.1109/LGRS.2025.3532346](https://doi.org/10.1109/LGRS.2025.3532346)

## 📝 Introduction
Change detection from synthetic aperture radar (SAR) imagery is critical in remote sensing research. Existing methods have made significant progress in the application of convolutional neural networks and attention mechanisms. However, traditional convolutional neural networks suffer the limitations in feature representation due to their depth and width constraints, and struggle to effectively capture complex interactions between image features. To address these issues, we propose a novel dynamic bilinear fusion network (DBFNet) for change detection in SAR imagery. First, to compensate for the lack of traditional convolutional representation capability, we design a dynamic shift convolution module that adaptively aggregates multiple convolution kernels and shifts pixels, enabling the extraction of richer and more detailed features. Second, a bilinear fusion module is designed to generate the bilinear joint representation between parallel features by computing a matrix outer product of feature maps. The paralel features include both intra-image and inter-image features, thereby effectively modeling the complex interactions and capturing the dependency relationship between spatio-temporal features. Experimental results on three real SAR datasets demonstrate the superior performance of DBFNet compared to existing state-of-the-art methods.

## 🚀 Installation
Our code is implemented in **PyTorch** and tested on **Google Colab** with a free GPU.

Cite：
H. Dong et al., "Dynamic Bilinear Fusion Network for Synthetic Aperture Radar Image Change Detection," in IEEE Geoscience and Remote Sensing Letters, vol. 22, pp. 1-5, 2025, Art no. 4004005, doi: 10.1109/LGRS.2025.3532346. keywords: {Convolution;Feature extraction;Radar polarimetry;Logic gates;Kernel;Synthetic aperture radar;Convolutional neural networks;Adaptation models;Transformers;Rivers;Bilinear pooling;change detection;dynamic convolution;synthetic aperture radar (SAR) image},

For any questions, please contact: Email: hhdongxd@163.com
