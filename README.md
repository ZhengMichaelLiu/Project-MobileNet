# Project-MobileNet
Implementation of MobileNet, trained and tested on CIFAR10
 
Paper: MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications. [read](https://github.com/ZhengMichaelLiu/Project-MobileNet/blob/master/MobileNets%20Efficient%20Convolutional%20Neural%20Networks%20for%20Mobile%20Vision%20Applications.pdf)

## Architecture

![architecture](architecture.png)

Input: 224 x 224 RGB images. Data in CIFAR10 has size 32 x 32, resize them to 224 x 224

Optimizer: Adam, with initial learning rate: 0.001

Scheduler: After each 20 epochs, the learning rate is decreased by 10 times.

## Result: Loss, Accuracy

![loss_acc](loss_acc.png)

Final Accuracy: 92.00%

## Under Construction

