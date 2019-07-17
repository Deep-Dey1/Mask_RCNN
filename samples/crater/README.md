# Detection and Segmantation of Martian Craters with MaskRCNN architecture.


1. [Data Preparation](https://github.com/mymultiverse/Mask_RCNN/edit/master/samples/crater#Data-Collection-and-Training-Validation-data-preparation)

2. [Data Inspection]()

3. [Training]()

4. [Testing]()

#### Data Collection and Training-Validation data preparation 
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

Dataset Source:

[ASU](https://jmars.mars.asu.edu/)

[USGS](https://webgis2.wr.usgs.gov/Mars_Global_GIS/)

