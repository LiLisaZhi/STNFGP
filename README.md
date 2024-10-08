# STNFGP
# STNFGP: Spatial-Temporal Non-Local Fine-Grained Perception for Land Cover Change Detection
## <img src="https://github.com/Lilith-ZZZ/STADE-CDNet_V1/blob/main/image/1%20(2).png" width="45" height="45">Requirements
<img src="https://github.com/Lilith-ZZZ/STADE-CDNet_V1/blob/main/image/33.png" width="15" height="15"><img src="https://github.com/Lilith-ZZZ/STADE-CDNet_V1/blob/main/image/33.png" width="15" height="15"><img src="https://github.com/Lilith-ZZZ/STADE-CDNet_V1/blob/main/image/33.png" width="15" height="15">
                

Conda create -n your_env_name python=3.8.0

Conda activate your_env_name

Conda install pytorch 1.10.1

Conda install torchvision 0.11.2

Conda install tqdm

Conda install numpy


                
<img src="https://github.com/Lilith-ZZZ/STADE-CDNet_V1/blob/main/image/33.png" width="15" height="15"><img src="https://github.com/Lilith-ZZZ/STADE-CDNet_V1/blob/main/image/33.png" width="15" height="15"><img src="https://github.com/Lilith-ZZZ/STADE-CDNet_V1/blob/main/image/33.png" width="15" height="15">              
## <img src="https://github.com/Lilith-ZZZ/STADE-CDNet_V1/blob/main/image/7.png" width="45" height="45"> Dataset Preparation


```
"""
Change detection data set with pixel-level binary labels;
                ├─A
                ├─B
                ├─label
                └─list
"""
```
`A`:image of pro-image;
`B`:image of post-image;
`label`:label maps;
`list`:contains train.txt, val.txt and test.txt, each file records the image names (XXX.png) in the change detection dataset.

## <img src="https://github.com/Lilith-ZZZ/STADE-CDNet_V1/blob/main/image/66.png" width="45" height="45">Links to download processed datsets
- LEVIR-CD:[`click here to download`](https://justchenhao.github.io/LEVIR/)
- DSIFN-CD: [`click here to download`](https://github.com/GeoZcx/A-deeply-supervised-image-fusion-network-for-change-detection-in-remote-sensing-images/tree/master/dataset)
- ISPR-CD :This data set was created by myself based on real-world data (from Synthetic images and read season-varying remote sensing images). If you require access to it, please let me know via email.
## <img src="https://github.com/Lilith-ZZZ/STADE-CDNet_V1/blob/main/image/7.png" width="45" height="45"> References 
Appreciate the work from the following repositories:
```
https://github.com/justchenhao/BIT_CD 
```
<img src="https://github.com/Lilith-ZZZ/STADE-CDNet_V1/blob/main/image/33.png" width="15" height="15"><img src="https://github.com/Lilith-ZZZ/STADE-CDNet_V1/blob/main/image/33.png" width="15" height="15"><img src="https://github.com/Lilith-ZZZ/STADE-CDNet_V1/blob/main/image/33.png" width="15" height="15"><img src="https://github.com/Lilith-ZZZ/STADE-CDNet_V1/blob/main/image/33.png" width="15" height="15"><img src="https://github.com/Lilith-ZZZ/STADE-CDNet_V1/blob/main/image/33.png" width="15" height="15"><img src="https://github.com/Lilith-ZZZ/STADE-CDNet_V1/blob/main/image/33.png" width="15" height="15"><img src="https://github.com/Lilith-ZZZ/STADE-CDNet_V1/blob/main/image/33.png" width="15" height="15"><img src="https://github.com/Lilith-ZZZ/STADE-CDNet_V1/blob/main/image/33.png" width="15" height="15"><img src="https://github.com/Lilith-ZZZ/STADE-CDNet_V1/blob/main/image/33.png" width="15" height="15">
```
https://github.com/wgcban/ChangeFormer
```

(The code implementation of our STADE-CDNet method references these code repoistories)
## <img src="https://github.com/Lilith-ZZZ/STADE-CDNet_V1/blob/main/image/16.png" width="45" height="45"> Contact
<img src="https://github.com/Lilith-ZZZ/STADE-CDNet_V1/blob/main/image/55.jpg" width="25" height="25">lisa_zhi@foxmail.com

