# SnorIAX | # EAGE Hackathon 2022

![SnorIAX](https://github.com/EAGE-Annual-Hackathon/SnorIAX/blob/main/logo.png)


Explainable AI repository for Porous media Generation (Discrimiantor Evaluation) and Salt Segmentation. 



## Main Objectives
- Use saliency and oclussion approaches to explain what the discrimanator is doing in a GAN example for porous media generation. 
- Use attention maps alongside the training for a salt segmentation problem. 

## Table of Contents
### Main Folders
This repository contains the following folders: 

**:open_file_folder:  Porous media:** 
  - It includes the models for each epoch (Generator and Discrimator) for a WGAN with gradient penalty for the Berea and Beadpack dataset. Also, it provides the visualization using saliency and oclussion approaches. 
  - Data needed for PorousMedia GAN:  https://drive.google.com/drive/folders/1Td-pGOgEzdyNLc9a53ZH20tzxfq2GwRq?usp=sharing
  
**:open_file_folder: AttentionSaltNet**
  - Salt segmentation problem focused on attention maps. 


**:open_file_folder: saltNet**
  - Not Successfull approach to apply saliency and oclussion approaches  :( sadly we did not manage to obtain good results. 





