# Joint Domain Adaptation with Weight Self-Learning for Hyperspectral Few-Shot Classification
JDAWSL project



## dataset

You can download the preprocessed source domain data set (Chikusei_imdb_128.pickle) directly in pickle format, which is available in "https://pan.baidu.com/s/1cbVzKSBxcWdOH5xGzwIlgA?pwd=5xk7" , and move the files to `./datasets` folder.

The QUH-Qingyun and QUH-Pingan datasets are available at: https://github.com/Hang-Fu/QUH-classification-dataset.

## example

An example dataset folder has the following structure:
```
datasets
├── Chikusei_imdb_128.pickle
├── IP
│   ├── indian_pines_corrected.mat
│   ├── indian_pines_gt.mat
├── SA
│   ├── ...
│   └── ...
├── QY
│   ├── ...
│   └── ...
└── Pa
    ├── ...
    └── ...
```

Meanwhile, for the convenience of saving the experimental results, we saved the model weights and prediction files to the `checkpoints` and `classificationMap` folders, the specific file structure is shown below.

```
checkpoints
├── IP
│   ├── model weight files...
├── SA
│   ├── ...
├── QY
│   ├── ...
│   └── ...
└── Pa
    ├── ...
    └── ...
    
classificationMap
├── IP
│   ├── prediction mat file
├── SA
│   ├── ...
├── QY
│   ├── ...
│   └── ...
└── Pa
    ├── ...
    └── ...

```
