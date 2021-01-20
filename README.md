# FCSMNet_LR

##train
train.sh

##inference
inference.sh

##tested env
CUDA10.2

NVIDIA-DRIVER 440.100

pytorch 1.5.0

python 3.6.9

tensorboard



##dataset supported
KITTI 2015

+ right ground truth disparity map

you can get from [here](https://github.com/yokosyun/kitti_leftDisp2rightDisp)



##model description

###input
left and right image

###output
leftDisp and rightDisp

###loss
ReconstructionLoss, DisparitySmoothnessLoss, LRconsistencyLoss, GroundTruthLoss
