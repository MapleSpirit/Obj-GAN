# Obj-GAN
## Obj-GAN - Official PyTorch Implementation

Pytorch implementation for reproducing Obj-GAN results in the paper [Object-driven Text-to-Image Synthesis via Adversarial Training](https://arxiv.org/pdf/1902.10740.pdf) by Wenbo Li*, Pengchuan Zhang*, Lei Zhang, Qiuyuan Huang, Xiaodong He, Siwei Lyu, Jianfeng Gao. (This work was performed when Wenbo was an intern with Microsoft Research).

<img src="example.png"/>

**Picture:** *The results of Obj-GAN is generated by the following two-step (layout-image) framework.*

<img src="framework.png"/>

### Dependencies
python 3.6

Pytorch 0.4.1

In addition, please add the project folder to PYTHONPATH and `pip install` the following packages:
- `python-dateutil`
- `easydict`
- `pandas`
- `torchfile`
- `nltk`
- `scikit-image`
- `spacy`
- `PyYAML`
- `cffi`
- `torchtext`
- `dill`
- `Cython`

**Data**


**Training**

**Pretrained Model**

**Sampling**


### Citing Obj-GAN
If you find Obj-GAN useful in your research, please consider citing:

```
@article{objgan19,
  author    = {Wenbo, Pengchuan Zhang, Lei Zhang, Qiuyuan Huang, Xiaodong He, Siwei Lyu, Jianfeng Gao},
  title     = {Object-driven Text-to-Image Synthesis via Adversarial Training},
  Year = {2019},
  booktitle = {{CVPR}}
}
