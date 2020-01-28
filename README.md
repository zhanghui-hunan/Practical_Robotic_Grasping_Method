# Practical_Robotic_Grasping_Method
1. download mvb dataset from http://volumenet.cn/#/
2.> mkdir MVB
   > mv MVB_train/Image       MVB/MVB_train/Image
   > mv MVB_val/Image/gallery MVB/MVB_val/Image/gallery
   > mv MVB_val/Image/probe   MVB/MVB_val/Image/probe
3. Install dependencies
     pytorch>=1.0
     torchvision
     yacs
     tensorboardX
4. pretrained model
   You can download the ImageNet pre-trained weights from here
   https://drive.google.com/drive/folders/1thS2B8UOSBi_cJX6zRy6YYRww_nVFI_S
