# EDSR-tensorflow2
Tensorflow 2 implementation of [Learning a Deep Convolutional Network for Image Super-Resolution](https://arxiv.org/abs/1501.00092).
![SRCNN](https://user-images.githubusercontent.com/45455072/82465244-08e5c980-9afa-11ea-8db2-0458af007012.png)  

## Usage
```
$ python main.py BATCH_SIZE=16 EPOCHS=200 N_TRAIN_TEST=800 N_TEST_DATA=100
```
### Prerequisites
- Python 3.7
- Tensorflow 2
- Numpy

## Directory
```
EDSR-tensorflow2
├── main.py              // main program
├── model.py             // edsr model
├── data_generator.py    // data augmentation
└── utils.py             // psnr, mae
```

## Sample Results
- trained by DIV2K
- test image set is Set14  

  
![sample](https://user-images.githubusercontent.com/45455072/91014943-468c4e00-e625-11ea-891e-ed2210184ba7.png)
