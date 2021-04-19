# GTAV_MultiView-SyntheticDataset-DomainAdaptation
## Breif Intro:  
The project is implemented with python and pytorch. Base model is Cyclegan and forward & backward SSIM losses are embedded. And some initial results are presented.  

Stage 1:  
<img src="https://github.com/KevynUtopia/GTAV_MultiView-SyntheticDataset-DomainAdaptation/blob/main/results/GTAV2Real/test_latest/images/1618489974_fake.png" width="150px"/>
<img src="https://github.com/KevynUtopia/GTAV_MultiView-SyntheticDataset-DomainAdaptation/blob/main/results/GTAV2Real/test_latest/images/1618489974_real.png" width="150px"/>
<img src="https://github.com/KevynUtopia/GTAV_MultiView-SyntheticDataset-DomainAdaptation/blob/main/results/GTAV2Real/test_latest/images/1618497624_fake.png" width="150px"/>
<img src="https://github.com/KevynUtopia/GTAV_MultiView-SyntheticDataset-DomainAdaptation/blob/main/results/GTAV2Real/test_latest/images/1618497624_real.png" width="150px"/>  
Comment: Virtual results seem not good

## Excutation:  
Please follow the [CycleGAN.ipynb](https://github.com/KevynUtopia/GTAV_MultiView-SyntheticDataset-DomainAdaptation/blob/main/CycleGAN.ipynb) to excute the training and testing. As the code was excuted on colab, the path should be configured specifically. 

## Acknowledgments:  
Codes are borrowed from [GCC-CL](https://github.com/gjy3035/GCC-CL), [Cycel GAN Base Model](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix) and [SSIM with pytorch implementation](https://github.com/Po-Hsun-Su/pytorch-ssim).
