# Vehicle-Detection-TensorFlow
**PROJECT:** PERFORMANCE COMPARISON OF DEEP LEARNING MODELS IN VEHICLE DETECTION FROM INPUT IMAGE

**Data source:** Victoria University Staff Library

**Dataset link:** https://vustaff-my.sharepoint.com/:u:/g/personal/e5112162_vu_edu_au/Ef0WSbY7uQtPi1HMHSQLhssB7mTvIFLpuHwy5u3A6x_wow?e=EhTLFr

**Data Description:** The collection contains about 17,760 images in 64*64*3 shape (vehicles:8,792 and non-vehicles:8,968), nearly 117MB in size.

**Train-test stratified Random Split:** 80:20 ratio (14208 training images and 3552 test images)

**Models used:** Custom MLP ANN, Custom CNN, Pre-trained EfficientNetV2S and Pre-trained MobileNetV3

**Best Test set Accuracy:** EfficientNetV2S (99% accuracy, FP=4, FN=2)

**Highest Training time:** EfficientNetV2S (18.33 mins)

**Lowest Training time:** Custom MLP ANN (1.28 mins)

