# Age, Gender, and Race Estimation with ResNet
Estimate age, gender, and ethnicity from facial images using a ResNet model.
![image](https://github.com/user-attachments/assets/aa695ad9-0686-463a-8671-d6187582c064)

This project utilizes the **UTK Faces** dataset, by cropping the facial region, to train two **ResNet** models for facial attribute estimation:
- **ResNet-50** for age estimation
- **ResNet-18** for gender and ethnicity classification

Dataset link: [UTK Faces](https://susanqq.github.io/UTKFace/)

Pretrained models are included in this repository for direct inference.

### Note
If running notebooks in **Google Colab**, set `system = "colab"` in the **Utils** section.  
For local execution, set `system = "local"`. 
