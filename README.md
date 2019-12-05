# Official implementation codes of the paper "Regularizing Neural Networks for Future Trajectory Prediction via Inverse Reinforcement Learning Framework"

 The paper is submitted to IET Computer Vision and now is under revision. If you want to see the ArXiv version of the paper, visit https://arxiv.org/abs/1907.04525

## Setup
All the codes were developed on Ubuntu 16.04 with Python 3.5 and Tensorflow 1.10.0. Two folders, **Crowd** and **SDD**, in the root directory contains 1) datasets, 2) trained models, and 3) the implementation codes respectively for **ETH/UCY** and **Standford Drone Dataset**. 

## Training New Models

To train the network from scratch, run the followings. The parameters of the trained networks will be stored at the folder ***saved_1_0***.
```sh
$ python crowd_train.py --dataset_num 1 --exp_id 0
$ python sdd_train.py --dataset_num 1 --exp_id 0
```

To test the trained model, run the followings. The program will automatically read the parameters of the train networks in the folder ***saved_1_0***.
```sh
$ python crowd_test.py --dataset_num 1 --exp_id 0
$ python sdd_test.py --dataset_num 1 --exp_id 0
```

## Pretrained Models
(Will be uploaded soon !!)
