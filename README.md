# PaDiM-Anomaly-Detection-Localization-master
This is an implementation of the paper [PaDiM: a Patch Distribution Modeling Framework for Anomaly Detection and Localization](https://arxiv.org/pdf/2011.08785).   

This code is heavily borrowed from both SPADE-pytorch(https://github.com/byungjae89/SPADE-pytorch) and MahalanobisAD-pytorch(https://github.com/byungjae89/MahalanobisAD-pytorch) projects
<p align="center">
    <img src="imgs/pic1.png" width="1000"\>
</p>

## Requirement
* python == 3.7
* pytorch == 1.5
* tqdm
* sklearn
* matplotlib

## Datasets
MVTec AD datasets : Download from [MVTec website](https://www.mvtec.com/company/research/datasets/mvtec-ad/)


## Results
### Implementation results on MVTec
* Image-level anomaly detection accuracy (ROCAUC)

|MvTec|R18-Rd100|WR50-Rd550|
|:---:|:---:|:---:|
|retinal| 0.72| 0.84|


* Pixel-level anomaly detection accuracy (ROCAUC)

|MvTec|R18-Rd100|WR50-Rd550|
|:---:|:---:|:---:|
|retinal| 0.7| 0.79|

### Localization examples

<p align="center">
    <img src="imgs/fundus_10.png" width="600"\>
</p>
<p align="center">
    <img src="imgs/fundus_13.png" width="600"\>
</p>
<p align="center">
    <img src="imgs/fundus_997.png" width="600"\>
</p>
## Reference
[1] Thomas Defard, Aleksandr Setkov, Angelique Loesch, Romaric Audigier. *PaDiM: a Patch Distribution Modeling Framework for Anomaly Detection and Localization*. https://arxiv.org/pdf/2011.08785

[2] https://github.com/byungjae89/SPADE-pytorch

[3] https://github.com/byungjae89/MahalanobisAD-pytorch

[4] https://github.com/xiahaifeng1995/PaDiM-Anomaly-Detection-Localization-master