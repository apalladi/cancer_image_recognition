# Cancer Image recognition

The purpose of this notebook is the creation of a Machine Learning algorithm to recognize the presence of cancer in images. 
The dataset, that has been used, is available on Kaggle https://www.kaggle.com/c/histopathologic-cancer-detection. The data must be unzipped and placed in the folder /data of the repository.
The dataset is quite big, since it contains more than 200.000 images, with a dimension of roughly 7 Gb. In order to run the algorithm locally, a computer with 16Gb of RAM is warmly suggested. 

The notebook is divided in 4 sections:
- 1 in the first section data are loaded. It is possible to load only a fraction of data;
- 2 in the section section data are visualized
- 3 the third section contains the Machine Learning algorithm. I have chosen a 5 layer Neural Network, with 2 convolution layers and 3 fully connected layers
- 4 in the last section an analysis of the performance is proposed
