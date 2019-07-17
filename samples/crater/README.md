# Mars Crater Detection and Segmantation with MaskRCNN

![](https://github.com/mymultiverse/Mask_RCNN/blob/master/samples/crater/gitex.PNG)

Detection of craters on planetary surface is very crucial for the better understanding of planet topography. It is also important for the selection of landing sites of various lander mission, path planning for rover missions. This project is about application of deep learning method for detection and semantic segmentation of craters in an image. Model trained using tranfer learning on pretrained MaskRCNN model. Overall project can be devided into four parts as follow:-    

1. [Data Preparation](https://github.com/mymultiverse/Mask_RCNN/edit/master/samples/crater#Data-Collection-and-Training-Validation-data-preparation)

2. [Data Inspection](https://github.com/mymultiverse/Mask_RCNN/blob/master/samples/crater/inspect_crater_data.ipynb)

3. [Training]()

4. [Testing]()

#### Data Collection and Training-Validation data preparation 

Image data collected from the [sources](Dataset-Sources) and annotated with [VIA](http://www.robots.ox.ac.uk/~vgg/software/via/via.html) tool to get json file. Which looks like:- 

![](https://github.com/mymultiverse/Mask_RCNN/blob/master/samples/crater/viaex.PNG)

The Labeled dataset can be downloaded from [dropbox](https://www.dropbox.com/s/iffj9aijkmrnx84/crater.zip?dl=0).
Dataset directory looks like:-
```bash

├── train
│   ├── img1.jpg
|   ├── :
|   ├── imgn.jpg
│   └── via_region_data.json
└── val
    ├── img.jpg
    ├── :
    ├── imgq.jpg
    └── via_region_data.json
```

Dataset Sources:

[ASU](https://jmars.mars.asu.edu/)

[USGS](https://webgis2.wr.usgs.gov/Mars_Global_GIS/)

