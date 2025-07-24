#Multi-Level Prototype Alignment for Cross-Domain Few-Shot Hyperspectral Image Classification
This is a code demo for the paper "Multi-Level Prototype Alignment for Cross-Domain Few-Shot Hyperspectral Image Classification"

##Requirements
CUDA = 11.3
Python = 3.8
Pytorch = 1.12.1

##dataset
1. target domain data set:

You can download the hyperspectral datasets in mat format at: http://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes, and move the files to `./datasets` folder.

2. source domain data set:

The source domain  hyperspectral datasets (Chikusei) in mat format is available in:https://pan.baidu.com/s/1Svt-8HC_FY3lQ1opO88X1A?pwd=6j42 
 
You can download the preprocessed source domain data set (Chikusei_imdb_128.pickle) directly in pickle format, which is available in "https://pan.baidu.com/s/1cbVzKSBxcWdOH5xGzwIlgA?pwd=5xk7" , and move the files to `./datasets` folder.
An example dataset folder has the following structure:
datasets
├── Chikusei_imdb_128.pickle
├── IP
│   ├── indian_pines_corrected.mat
│   ├── indian_pines_gt.mat
├── houston
│   ├── houston.mat
│   └── houston_gt.mat
└── paviaU
    ├── paviaU_gt.ma
    └── paviaU.mat
```    
