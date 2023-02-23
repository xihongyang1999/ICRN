[stars-img]: https://img.shields.io/github/stars/xihongyang1999/ICRN?color=yellow
[stars-url]: https://github.com/xihongyang1999/ICRN/stargazers
[fork-img]: https://img.shields.io/github/forks/xihongyang1999/ICRN?color=lightblue&label=fork
[fork-url]: https://github.com/xihongyang1999/ICRN/network/members
[visitors-img]: https://visitor-badge.glitch.me/badge?page_id=xihongyang.1999.ICRN/
[adgc-url]: https://github.com/xihongyang1999/ICRN

# Interpolation-based Correlation Reduction Network for Semi-Supervised Graph Learning

<p align="center">   
    <a href="https://pytorch.org/" alt="PyTorch">
      <img src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?e&logo=PyTorch&logoColor=white" /></a>
    <a href="https://cis.ieee.org/publications/t-neural-networks-and-learning-systems" alt="Journal">
        <img src="https://img.shields.io/badge/IEEE TNNLS'22-brightgreen" /></a>
<p/>


[![GitHub stars][stars-img]][stars-url]
[![GitHub forks][fork-img]][fork-url]
[![visitors][visitors-img]][adgc-url]


An official source code for paper Interpolation-based Correlation Reduction Network for Semi-Supervised Graph Learning.  Any communications or issues are welcomed. Please contact xihong_edu@163.com. If you find this repository useful to your research or work, it is really appreciate to star this repository. :heart:

-------------

### Overview

<p align = "justify"> 
 Illustration of Interpolation-based Correlation Reduction Network for Semi-Supervised Graph Learning (ICRN) mechanism. 
</p>
<div  align="center">    
    <img src="./assets/overall.png" width=60%/>
</div>








### Requirements

The proposed ICRN is implemented with python 3.8.8 on a NVIDIA 1080 Ti GPU. 

Python package information is summarized in **requirements.txt**:

- torch==1.8.0
- tqdm==4.61.2
- numpy==1.21.0
- tensorboard==2.8.0



### Quick Start

```
python train.py 
```



### Citation

If you use code or datasets in this repository for your research, please cite our paper.

```
@article{ICRN,
  title={Interpolation-based correlation reduction network for semi-supervised graph learning},
  author={Yang, Xihong and Liu, Yue and Zhou, Sihang and Liu, Xinwang and Zhu, En},
  journal={arXiv preprint arXiv:2206.02796},
  year={2022}
}

```

