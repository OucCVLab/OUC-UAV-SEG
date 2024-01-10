# OUC-UAV-SEG
<div align="center">
  <img src="https://github.com/OucCVLab/OUC-UAV-SEG/raw/main/haibao.jpg" width="300" alt="Image">
</div>

### News
- **2024.1.8** Our paper "A semantic segmentation benchmark dataset for coastal ecosystem monitoring based on Unmanned Aerial Vehicle (UAV) " is **accepted** by CSIG(中国图象图形学报)  !
- **2023.9.15** OUC-UAV-SEG released with all images and annotations for training and vallidation!
### Motivation
- Coastal ecosystems are crucial for maintaining a high-quality ecological environment and enriching marine biodiversity. However, there is currently an issue with the lack of comprehensive and detailed data support for the classification and zoning of coastal ecosystems.
- Due to the combined influence of natural environmental factors and human activities, the external morphology of coastal zones changes rapidly. The existing monitoring methods such as satellite remote sensing and conventional manual measurements, as well as ship-based operations, are no longer sufficient to meet the requirements for real-time observations.
- We utilized a versatile drone platform to collect images of typical coastal ecosystem communities along the Qingdao coastline and created the OUC-UAV-SEG dataset, which we subsequently annotated.
- Our aim is for this dataset to assist scientists, ecologists, and decision-makers in gaining a better understanding of the current status and trends of coastal ecosystems. We intend to provide crucial information for more precise marine ecological conservation and management.

### Description
The OUC-UAV-SEG dataset comprises a total of 726 images, with 477 in the training set, 140 in the validation set, and 109 in the test set. However, it's important to note that **the annotations for the test set have not been made public**. You can use your own trained model for online evaluation on the [website](http://www.cvlab-ouc.cn/#/index).
![OUC-UAV-SEG](OUC.png)
### Download
OUC-UAV-SEG is organized in the following format:
```
OUC-UAV-SEG
├─gt_jpg
│  ├─train
│  ├─val
│  └─test
└─label_png
    ├─train
    └─val
```
It can be obtained from the following link:
- [Google Drive](https://drive.google.com/file/d/17ebUnIegQxWGeOyr-JeBraqJCkHJJTM3/view?usp=sharing)
- [百度网盘(提取密码：OUC1)](https://pan.baidu.com/s/1FnZEuSD4MLsd6-efB2G8vQ)


### Citation
If you make use of the OUC-UAV-SEG dataset, please cite our following paper:
```

```

### Contact
If you have any questions, you can contact Xiandong Wang. 

Email: wangxiandong@stu.ouc.edu.cn
