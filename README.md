# Transfer-learning-in-MRI

This project implements Transfer learning techniques on brain tumor images.
Database: https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection/
Pre-trained models trained on small database (253 images) and demonstrate significant ability to perform classification and segmentation tasks.
There are 2 folders:
- Classification: base model is InceptionResNetV2 pretrained on ImageNet
- Segmentation: base model is Mask R-CNN pretrained on COCO (run requirements2.txt with "cat requirements2.txt | xargs -n 1 pip instal")

Every folder has requirements.txt file 
