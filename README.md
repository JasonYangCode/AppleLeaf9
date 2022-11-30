## 1.Keywords
Apple leaf disease; Plant disease; Crop diseases; Image classification dataset; Fine-grained image classification

## 2.Dataset description
The fusion of the four datasets [1-3]can make the proposed model identify more categories of apple leaf diseases (ALDs) in the wild environment, which enhances the model’s ability to cope with environmental changes, thus making the proposed model more robust. Therefore, in this paper, the dataset called AppleLeaf9 was fused from PlantVillage dataset (PVD) [1], apple tree leaf disease segmentation dataset (ATLDSD) [2], PPCD2020 [3], and PPCD2021 [3]. AppleLeaf9 will help agricultural practitioners better apply CNN models to solve more ALD practical problems. Agricultural disease experts were invited to screen each image, and images with incorrect labels were removed. In the process of data fusion, some static background images were reduced. Since PVD contains only static background images, only 2.5% of all images in AppleLeaf9 are from PVD. At the same time, since some disease categories of ATLDSD, PPCD2020, and PPCD2021 are the same, AppleLeaf9 fuses partial images of the three datasets. The AppleLeaf9 dataset contains 14,582 images, 94% in the wild environment. The distribution of AppleLeaf9’s image sources is shown in Figure 1. The samples of AppleLeaf9 are shown in Figure 2.  
<image src="./Figure 1.jpg" width="400">

<center>Figure 1. Distribution of image sources in AppleLeaf9.</center>

<image src="./Figure 2.jpg" width="400" height="400">
<center>Figure 2. Samples of AppleLeaf9: (a) healthy; (b) Alternaria leaf spot; (c) brown spot; (d) frogeye leaf spot; (e) grey spot; (f) mosaic; (g) powdery mildew; (h) rust; and (i) scab.</center>



[1] Hughes, David, and Marcel Salathé. "An open access repository of images on plant health to enable the development of mobile disease diagnostics." arXiv preprint arXiv:1511.08060 (2015).  
[2] Jingze Feng, Xiaofei Chao. Apple Tree Leaf Disease Segmentation Dataset[DS/OL]. Science Data Bank, 2022[2022-11-30]. https://doi.org/10.11922/sciencedb.01627  
[3] Thapa, Ranjita, et al. "The Plant Pathology Challenge 2020 data set to classify foliar disease of apples." Applications in Plant Sciences 8.9 (2020): e11390. https://doi.org/10.1002/aps3.11390

## 3.Cite this dataset
Yang, Qing, Shukai Duan, and Lidan Wang. "Efficient Identification of Apple Leaf Diseases in the Wild Using Convolutional Neural Networks." Agronomy 12.11 (2022): 2784. https://doi.org/10.3390/agronomy12112784

