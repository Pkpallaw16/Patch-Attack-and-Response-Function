# Patch Attack and Response Function
Welcome! This repository outlines details of the my Computer Vision based project - Patch Attack and Response Function.
## Project Summary
The objective of this project is to investigate the vulnerability of autonomous driving perception systems to a patch attack (Goldfish attack). The patch attack is a physical black box attack that involves adding overlapping images or patches onto traffic signs with the intention of deceiving autonomous vehicles.
## Approach and Methodology
The project is devided into three components: 
1. Building image classification model using ResNet-50 architecture. This architecture is not suitable for adversial attacks images classification but due to hardware limitations it was one of the best options.
2. Constructing and Analysis of Confidence Surface Function
3. Algorithm Optimation and Evaluation
## Result
Few results from #2 analysis.

![image](https://github.com/user-attachments/assets/4e748f5d-9a84-4b21-9451-c1a3538c4b9a)
![image](https://github.com/user-attachments/assets/b00d9b65-317f-46f4-b4da-a916965d3c1e)

## Fun Fact
Example 1: Resnet-50 model prediction on few images were incorrect before FGSM attack however, the prediction was correct on patch attached images.

![image](https://github.com/user-attachments/assets/0b499920-96fe-416a-ba40-fad14692ffb4)

## Tools & Technologies
- **Programming**: Python
- **Frameworks/Libraries**: torchvision, PyTorch
- **Neural Networks**: ResNet50 
- **IDE**: Google Colab

Hit like button! :)
