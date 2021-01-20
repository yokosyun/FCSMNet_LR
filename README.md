# FCSMNet_LR

<h2>train</h2>
train.sh

<h2>inference</h2>
inference.sh

<h2>tested env</h2>
+ CUDA10.2
+ NVIDIA-DRIVER 440.100
+ pytorch 1.5.0
+ python 3.6.9
+ tensorboard



<h2>dataset supported</h2>
+ KITTI 2015(leftImg, rightImg, DispLeft,(DispRight))
  you can get right disparity map from [here](https://github.com/yokosyun/kitti_leftDisp2rightDisp)



<h2>model description</h2>

<h3>input</h3>
left and right image

<h3>output</h3>
leftDisp and rightDisp

<h3>loss</h3>
ReconstructionLoss, DisparitySmoothnessLoss, LRconsistencyLoss, GroundTruthLoss
