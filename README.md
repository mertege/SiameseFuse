# SiameseFuse
A Deep Siamese Approach for Visible and Infrared Images.
# Notes
By downloading SiameseFuse_Keras.ipynb file, you can run the Keras code of SiameseFuse architecture. 

## Dataset
In order to load dataset for test and training you can use following links:


### Training

* [Thermal](https://drive.google.com/file/d/15t-KSXSoHfv09del8T1OmFPA8d9GuVQb/view?usp=sharing "Thermal Training Data")

* [Grayscale](https://drive.google.com/file/d/1grvxahI65Bm-GLLTAFob9Z8lZuFfHO2s/view?usp=sharing "Grayscale Training Data")

 ### Testing
 
* [Thermal](https://drive.google.com/file/d/1VXlElPSCBGcu7Ls5L_DIvUUYFHczcQDP/view?usp=sharing "Thermal Test Data")

* [Grayscale](https://drive.google.com/file/d/1uGB8CKWptg4gzMQajpzUVH8Pru0V3-AO/view?usp=sharing "Grayscale Test Data")

# Abstract
In recent years, image processing field is making great progress thanks to deep learning methods. Hence, fusing infrared and visible images also benefited from deep learning architectures. However, there is no architecture that feeding directly thermal and visible images at the same time to train their model. Therefore, features of thermal and visible images cannot be extracted properly. In this paper, large amount of the overlapped thermal and visible images have been gathered to train our model using Siamese and CNN-based architecture, termed as SiameseFuse. The proposed architecture uses 2 ground truth images including thermal and visible images to get loss of architecture. We further show that proposed method gives state-of-the-art performance with smaller parameter numbers on variety of images in both subjective and objective assessment.
# SiameseFuse Architecture
![alt text](https://github.com/mertege/SiameseFuse/blob/master/figures/SiameseFuse.PNG)
# Results

![alt text](https://github.com/mertege/SiameseFuse/blob/master/figures/fused_images.png)
