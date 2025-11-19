# 1 SSDATFO
Repository for the paper: Style-Guided Source Data Augmentation and Target Feature Optimization for Cross-Domain Few-Shot Image Classification

The code is currently undergoing organization, and only a portion of it has been released. The complete code will be made available in the near future.

# 2 Setup 
## 2.1 conda env & code
```
# conda env
conda create --name py36 python=3.6
conda activate py36
conda install pytorch torchvision -c pytorch
conda install pandas
pip3 install scipy>=1.3.2
pip3 install tensorboardX>=1.4
pip3 install h5py>=2.9.0
pip3 install tensorboard
pip3 install timm
pip3 install opencv-python==4.5.5.62
pip3 install ml-collections
# code
git clone https://github.com/lqjoy/SSDATFO
cd SSDATFO
```
## 2.2 datasets
We use the mini-Imagenet as the single source dataset, and use cub, cars, places, plantae, ChestX, ISIC, EuroSAT, and CropDisease as novel target datasets. 

For the mini-Imagenet, cub, cars, places, and plantae, we refer to the [FWT](https://github.com/hytseng0509/CrossDomainFewShot) repo.

For the ChestX, ISIC, EuroSAT, and CropDisease, we refer to the [BS-CDFSL](https://github.com/IBM/cdfsl-benchmark) repo.

# Acknowledge
Our code is built upon the implementation of [StyleAdv-CDFSL](https://github.com/lovelyqian/StyleAdv-CDFSL), [FWT](https://github.com/hytseng0509/CrossDomainFewShot), [ATA](https://github.com/Haoqing-Wang/CDFSL-ATA), and [PMF](https://github.com/hushell/pmf_cvpr22). Thanks for their work.
