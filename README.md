# :paperclip: Artificial neural networks and deep learning -Project
This is the repository for the projects of the Artificial neural networks and deep learning course held at [Polimi](https://www.polimi.it/).

2 different project were developed to apply all the topics of the course. For each project a dataset is provided, no external images are allowed. The goal is to train a good-performing network to solve a specific task. An external dataset is used to test the network. [Kaggle](https://www.kaggle.com/) was used to develop (and train) the networks

### 1) Image Classification Challenge 🍃
Given a  [dataset](https://www.kaggle.com/datasets/giuseppecalcagno/an2dl-challenge) of plant images (96x96), the goal of the project is to classify them according to 8 classes.

<div align="center">


![1](https://user-images.githubusercontent.com/94358195/224503443-fe261884-7ab4-48aa-bdbc-614352ec2748.jpg)
![5](https://user-images.githubusercontent.com/94358195/224503439-f3127aad-8748-4d55-818b-26b859fb869a.jpg)
![4](https://user-images.githubusercontent.com/94358195/224503440-43ff1eed-3352-40a7-8ab9-392973204408.jpg)
![3](https://user-images.githubusercontent.com/94358195/224503441-7b105306-f8f6-47fc-8acd-af692074e582.jpg)
![2](https://user-images.githubusercontent.com/94358195/224503442-595169c1-e556-4f26-8256-6a5cae3c6f9d.jpg)
![8](https://user-images.githubusercontent.com/94358195/224503444-21f5a73d-73b6-495b-a1cc-159fb7b8e723.jpg)
![7](https://user-images.githubusercontent.com/94358195/224503445-be179301-2869-4477-89fa-974f7c5ddb1d.jpg)
![6](https://user-images.githubusercontent.com/94358195/224503446-70a65bf5-9c84-4adc-9db7-4dbea41a213f.jpg)

</div>

In order to archive the best result and learn the main difficulties of the developing, me and my team decided to follow this steps:
* Convolutional Neural Network from scratch
* Data Augmentation 
* Transfer Learning approach 

📚 A final [report](https://github.com/GppCalcagno/AN2DL-Project/blob/main/Challenge%20%201/Report.pdf) is available in which all the phases of the project are described in detail.

🏆 At the end of the challenge, we reached an accuracy of 0.914 on the platform test set with our best model

##

### 2) Time-Series Classification Challenge ⏱

In this task, we are required to correctly classify among 12 possible labels samples from 6 different time series in the multivariate time series format. The Dataset is available [on kaggle](https://www.kaggle.com/datasets/giuseppecalcagno/an2dl-challenge2)

<div align="center">
  
  ![image](https://user-images.githubusercontent.com/94358195/224504823-4f121c63-6b94-4f32-9a64-07a0771dfb73.png)

</div>

In order to archive the best result and learn the main difficulties of the developing, me and my team decided to follow this steps:
* Conv1D and LSTM Network
* Data Augmentation 
* ResNet Style Architectures 

📚 A final [report](https://github.com/GppCalcagno/AN2DL-Project/blob/main/Challenge%202/Report.pdf) is available in which all the phases of the project are described in detail.

🏆 At the end of the challenge, we reached an accuracy of 0.7394 on the platform test set with our best model

---
✔️ Final Evaluation: 10/11

