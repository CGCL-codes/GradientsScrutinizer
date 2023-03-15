# Gradients_Scrutinizer
The implementation of NDSS 2023 paper "Focusing on Pinocchio's Nose: A Gradients Scrutinizer to Thwart Split-Learning Hijacking Attacks Using Intrinsic Attributes".

### Note:
This is modified from [SplitNN_FSHA](https://github.com/pasquini-dario/SplitNN_FSHA), which is the source code of the CCS'2021 Paper [Unleashing the Tiger: Inference Attacks on Split Learning](https://arxiv.org/abs/2012.02670)

## Introduction
This repository contains the code that implements the SplitSpy and Gradients Scrutinizer described in our paper "Focusing on Pinocchio's Nose: A Gradients Scrutinizer to Thwart Split-Learning Hijacking Attacks Using Intrinsic Attributes" published at NDSS 2023. 

## Requirements
Our code is implemented and tested on python 3.6 and TensorFlow 
Install all the requirements by:
`pip install requirements.txt`
or install with conda by:
`conda env create -f requirements.yml`
`conda activate GradientsScrutinizer`

## SplitSpy
Working on code releasing

## Gradients Scrutinizer
The implementation of Gradients Scrutinizer is under the path `\GradientsScrutinizer\`.
The script `example.py` can be used to reproduct our experiments of detecting FSHA training from honest SL training. It can be done by:
`python example.py`
This script includes the training of FSHA client and server models and honest client and server models, and the detction score calculation.

## Citation

If you are using our code for research purpose, please cite our paper.

```
@inproceedings{gradientsscrutinizer_ndss202,
  author    = {Jiayun Fu, Xiaojing Ma, Bin B. Zhu, Pingyi Hu, Ruixin Zhan, Yaru Jia, Peng Xu, Hai Jin, and Dongmei Zhang},
  title     = {Focusing on Pinocchio's Nose: A Gradients Scrutinizer to Thwart Split-Learning Hijacking Attacks Using Intrinsic Attributes},
  booktitle = {30th Annual Network and Distributed System Security Symposium, {NDSS}
               2023, San Diego, California, USA, February 27-March 3, 2023},
  publisher = {{The Internet Society}},
  year      = {2023},
  url       = {https://www.ndss-symposium.org/wp-content/uploads/2023/02/ndss2023_f874_paper.pdf}
}
```

