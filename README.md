# Conv-attention ViT

This repo is the official implementation of ["Conv-attention ViT for classification of multi-label class imbalanced data of lung thoracic diseases"](https://link.springer.com/article/10.1007/s11042-024-20363-z). The repo is based on the timm library (https://github.com/rwightman/pytorch-image-models) by [Ross Wightman](https://github.com/rwightman)

## Introduction

**Conv-attention ViT** 
Conv-Attention Vision Transformer (CA-ViT) for the classification of lung thoracic diseases from chest X-ray images. The proposed technique is presented in Figure 2. There are three steps in the proposed methodology: data augmentation, image pre-processing and classification using proposed model CA-ViT. This paper will be focusing on classification of thoracic abnormalities namely: Aortic enlargement, Atelectasis, Pneumothorax, Cardiomegaly, Consolidation, Nodule/Mass, Pleural thickening, Lung Opacity, Other lesion, Infiltration, Pleural Effusion, Calcification, Pulmonary fibrosis and ILD. These thoracic abnormality chest X-ray images are found in VinDr-CXR dataset [34], Chest X-ray14 dataset [50], CheXpert dataset [29] and PadChest dataset [5]. In this work, chest X-ray images are taken from all these datasets as each dataset is highly class imbalanced.

## Citing DeepVit

```
@article{article,
author = {Oommen, Lintu and Nagajyothi, Chiluka and Chebrolu, Srilatha},
year = {2024},
month = {11},
pages = {1-30},
title = {Conv-attention ViT for classification of multi-label class imbalanced data of lung thoracic diseases},
journal = {Multimedia Tools and Applications},
doi = {10.1007/s11042-024-20363-z}
}
```




