# MobileNet Implemetation:
##### Yassin Bahid

### Summary:
Since AlexNet, Deep Neural Networks have become ubiquitous. However, the evermore large and more complex architectures have solely focused on accuracy to the detriment of Latency and speed. While reaching high levels of accuracy is excellent when one has access to powerful systems, they are less practical when using smaller machines such as smartphones. A. Howard's answer to this problem is his MobileNet architecture from his 2017 Paper. We shall explore the first two versions of this architecture. We shall then compare the latency and accuracy of the model. In order to mimic the slow performance of certain machines, we shall compare the times needed to commpute accuracies on the test data on the CPU.


### File Structure:
\item Small_Networks.ipynb: Jupyter Notebook containing report.
\item MobileNetV1.pt: Trained MobileNet V1 Architecture
\item MobileNetV2.pt: Trained MobileNet V2 alpha = 1 Architecture
\item MobileNetV250.pt: Trained MobileNet V2 alpha = 0.5 Architecture
\item MobileNetV275.pt: Trained MobileNet V2 alpha = 0.75 Architecture
#### Reference:
Howard, Andrew G., et al. MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications. arXiv, 16 Apr. 2017. arXiv.org, http://arxiv.org/abs/1704.04861.

CIFAR10, https://www.cs.toronto.edu/~kriz/cifar.html.

Resnet9, https://www.kaggle.com/code/kmldas/cifar10-resnet-90-accuracy-less-than-5-min