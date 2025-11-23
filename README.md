# Robust-Retinex
The official code of [*"A Robust Deep Retinex Decomposition Network Leveraging a Novel Synthetic Dataset for Low-Light Image Enhancement"*](https://ieeexplore.ieee.org/document/11152121)
> 📝 Published in: IEEE International Conference on Multimedia and Expo Workshops (ICMEW), 2025  
> 🧑‍💻 Author: [Kaicheng Xu](https://github.com/Kylesesa), An Wei, Congxuan Zhang, Zhen Chen, Peng Liu, and Ke Lu.


## Datasets

<p align="center">
  <img src="viewpoint.png" alt="viewpoint" width="90%">
</p>
<p align="center">
    A set of example images from a single viewpoint in our PRI dataset.(a) The rendered image in normal-light conditions. (b) The illumination image in normal-light conditions. (c) The rendered image in low-light conditions. (d) The illumination image in low-light conditions.
</p>


<p align="center">
  <img src="sample.png" alt="sample" width="45%">
</p>
<p align="center">
    Some examples from our PRI dataset.

If you want the datasets, please email me.
</p>


## Overall Framework


<p align="center">
  <img src="framework.png" alt="overview" width="90%">
</p>
<p align="center">
    The workflow of our robust Retinex decomposition method.
</p>

## Environment

```latex
Python = 3.7.16
PyTorch = 1.11.0
torchvision = 0.12.0
numpy = 1.19.5，
matplotlib = 3.5.3
opencv-python = 4.8.0.76
```
Please make sure all dependencies are installed. If certain packages are missing, please install them manually. If you are unable to set up the environment successfully, please contact me.

## Train 
I've been quite busy lately, but I'll upload the code as soon as possible. Our network and loss function are both very straightforward—you can fully build it by following the paper exactly.

## Test

## Citation
```latex
@INPROCEEDINGS{xu2025robust,
  author={Xu, Kaicheng and Wei, An and Zhang, Congxuan and Chen, Zhen and Liu, Peng and Lu, Ke},
  booktitle={2025 IEEE International Conference on Multimedia and Expo Workshops (ICMEW)}, 
  title={A Robust Deep Retinex Decomposition Network Leveraging a Novel Synthetic Dataset for Low-Light Image Enhancement}, 
  year={2025},
  volume={},
  number={},
  pages={1-6},
  doi={10.1109/ICMEW68306.2025.11152121}}
```
