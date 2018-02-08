# py_Lightened_CNN
Python version of Lightened CNN for face feature extraction. For technique details, please refer to the [original paper](https://arxiv.org/pdf/1511.02683v1.pdf).

## Demo

## Datasets
### CASIA-WebFace
#### Download training dataset
Require CASIA-WebFace datasets from [here](http://www.cbsr.ia.ac.cn/english/CASIA-WebFace-Database.html).

Download and unextract the dataset:
```
unrar x $DATASET_RAR $EXTRACTED_DIR
```
Generate file list such that in each line listed one image patch and its class label.
```
# map pics to contiguous label
$ cd ${FACIAL_BASE_SCRIPT}
$ python label2pic.py ${DATA_ROOT}
```

#### Preprocessing

### LFW
#### Downlaod dataset
#### Preprocessing

## Training
## Evaluation
