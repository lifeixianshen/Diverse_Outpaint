# Multimodal Image Outpainting
This is a Pytorch implementation of our paper "Multimodal Image Outpainting". 

[Multimodal Image Outpainting With Regularized Normalized Diversification](https://arxiv.org/abs/1910.11481) <br />
[Lingzhi Zhang](https://owenzlz.github.io/), Jiancong Wang, [Jianbo Shi](https://www.cis.upenn.edu/~jshi/)  <br />
GRASP Laboratory, University of Pennsylvania

## Introduction

We study the problem of generating a set of realistic and diverse backgrounds when given only a small foreground region, which we formulate as image outpainting task. We propose a generative model by improving the normalized diversification framework to encourage diverse sampling in this conditional synthesis task. The results show that our proposed approach can produce more diverse images with similar or better quality compare to the state-of-the-arts methods.

<img src='demo_imgs/demo.png' align="middle" width=720>

## Usage

[TODO]


## Synthetic Results Comparison

<img src='demo_imgs/synthetic_results.png' align="middle" width=720>

## Face Examples

<img src='demo_imgs/sampled_face.png' align="middle" width=720>

## Street Scene Examples

<img src='demo_imgs/sampled_city.png' align="middle" width=720>



## Citation
If you use this code for your research, please cite our [paper](https://arxiv.org/abs/1910.11481):

```
@article{zhang2019multimodal,
  title={Multimodal Image Outpainting With Regularized Normalized Diversification},
  author={Zhang, Lingzhi and Wang, Jiancong and Shi, Jianbo},
  journal={arXiv preprint arXiv:1910.11481},
  year={2019}
}
```
