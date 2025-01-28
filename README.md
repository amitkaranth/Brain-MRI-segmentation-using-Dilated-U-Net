# Brain-MRI-segmentation-using-Dilated-U-Net
The project involved using Brain MRI images (sourced from the BRATS2020 dataset) to segement parts of the image as tumorous and non-tumorous. A modified version of the U-Net model has been used, where certain CNN layers in the model are replaced with dilated CNN layers for better feature capturing.

Although the BRATS2020 dataset contains over 35000 MRI images, we have utilized around 15000 images for the training and validation of the model.

Please find the link to the modified dataset on kaggle here:
https://www.kaggle.com/datasets/amitkaranth/brats15k-dataset/data
