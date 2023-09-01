# Need a NVIDIA graphic card for CUDA

Demanding on the hardware, certain steps with a big epoch numbers should be ran overnight. Also monitor the temperature


# Pytorch_Medical_Image

Update code as of August 2023.

Need to change the directory within these files according to your own computer. 


The final model of 07-Capstone has a Val Dice Score is:  0.22702382504940033


In the context of image segmentation tasks in machine learning,a Dice score close to 1 indicates perfect overlap (i.e., perfect segmentation),


while a score close to 0 indicates no overlap. Closer to 1 is better


This low score might be due to the low number of epoch = 10 instead of 30. This is due to the limitation of my hardware


10 epochs cost me 4.5 hours, so the default 30 epochs should be around 14 hours...



[Capstone Project-1](07-CAPSTONE-PROJECT--Lung-Tumor-Segmentation/1.png)

[Capstone Project-Final-Lung](07-CAPSTONE-PROJECT--Lung-Tumor-Segmentation/Final_lung_model_10_epochs.mp4)

[Capstone Project-2](07-CAPSTONE-PROJECT--Lung-Tumor-Segmentation/2.png)
