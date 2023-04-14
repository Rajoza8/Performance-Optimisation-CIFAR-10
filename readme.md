# ECE-GY 7123 Deep Learning Mini Project

The objective of our  miniproject is to design a modified ResNet architecture for image classification on the CIFAR-10 dataset, under the parameter budget constraint of 5 mil-lion. To achieve this goal, we experimented with various design choices (explained at length in the Methodology section of our report) and came up with a modified version of the ResNet-18 architecture, with 4 residual layers, with 1 block per layer. The model performs fairly well after data augmenta-tion and learning rate scheduling and weight decay, rendering a test accuracy of 91%, while the parameter count is 4903242, i.e., around 4.9 million, within the provided limit.


## Submitted by
* Yashika Khurana (yk2773)
* Raj Oza (ro2151)
* Amey Kolhe (apk9563)

## System Specs
* MacOS Big Sur 11.0.1
* Processor: 2.3 GHz Dual-Core Intel Core i5
* Memory: 8GB
* Python: 3.8.0
* Torch 2.0.0
* Graphics: Intel Iris Plus 640 1536 MB






