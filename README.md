# Sparse2dense: Sparse to Dense Dynamic 3D Facial Expression Generation

This is an official repository of the paper Sparse to Dense Dynamic 3D Facial Expression Generation. https://arxiv.org/abs/2105.07463


# Results

- 4D Facial expression generation
 
![tst_githubvideo_4](https://user-images.githubusercontent.com/19242829/158143735-a38fece3-75ed-4d4e-b873-bb167624c846.gif)


- Interpolation between 4D facial expressions 
 
![tst_githubvideo_2](https://user-images.githubusercontent.com/19242829/158142211-174651ec-0f46-4ebd-8a3d-0564f24b77a4.gif)
![tst_githubvideo_3](https://user-images.githubusercontent.com/19242829/158142959-7887841e-8a48-43d1-9f07-9371af8cbb09.gif)

- Speech transfer 

![tst_githubvideo](https://user-images.githubusercontent.com/19242829/158222004-abf2e76b-362e-48e8-b859-aa5fb4070234.gif)


# Usage
The code is divided into two folders: 

Motion3DGAN: used to train a GAN generator of 3D landmarks motion;

S2D: used to train and test the decoder that deforms the 3d mesh according to a given landmarks configuration;

You will find a Readme file inside each one of these folders with the installation and the usage instructions.

# Models
Please download models from the link below and include them in S2D\Models folder.

https://drive.google.com/drive/folders/1-RdBhUfP7JcxihVCT4AdLRYfSBOD9Rmq?usp=sharing

# Reference
Please cite the following paper if you use the code directly or indirectly in your research/projects.

<div class="snippet-clipboard-content position-relative overflow-auto" data-snippet-clipboard-copy-content="@inproceedings{otberdout2022sparse,
title = {Sparse to Dense Dynamic 3D Facial Expression Generation},
author = {Otberdout, Naima and Ferrari, Claudio and Daoudi, Mohamed and Berritti, Stefano and Del Bimbo, Alberto},
booktitle = {Proceedings IEEE Conf. on Computer Vision and Pattern Recognition (CVPR)},
month = jun,
year = {2022},
}"><pre><code>@inproceedings{otberdout2022sparse,
title = {Sparse to Dense Dynamic 3D Facial Expression Generation},
author = {Otberdout, Naima and Ferrari, Claudio and Daoudi, Mohamed and Berritti, Stefano and Del Bimbo, Alberto},
booktitle = {Proceedings IEEE Conf. on Computer Vision and Pattern Recognition (CVPR)},
month = jun,
year = {2022},
}
