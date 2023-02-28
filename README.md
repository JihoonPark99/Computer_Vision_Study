# Computer_Vision_Study

This is study of myself about computer vision.
We will study about 
- Neural Network
- Transfer Learning
- VggNet
- Aumentation 
- GoogLeNet
- ResNet

---

## Week1
**Neural Network**
1. Difference with ML and Deep Learning
2. ANN
3. CNN
4. Gradient Vaninshing and Overfitting

HomeWork
[kaggle URL](https://www.kaggle.com/code/uzairrj/beg-tut-intel-image-classification-93-76-accur/notebook)


![Accuracy](https://www.kaggleusercontent.com/kf/16898899/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..ptYEf57h6fXoNWEi7lYElA.jqvd2W6OqCbvF86nu01GCnFF77pojO0gHxd-rjcrKujvgjI1L2LfaqyQ0A-YBFB7fK8CK9iDkEBrYfMwRRCr2kVw8F_KOygvRUHSWl5YsF5aCfhSMZoTxdv68_Xv_e_6g5yZDKECh8vtZBK7PFrfsCzO8id9GZe0ifs_FxwT356u5H-DHbkj370s9KCgAk5kC-_Ow6wg6XJ2EJ-I0h2sRQkdOLI1rvHUd7w297KroDb3mgo1oukgMQCURkgvJF9HWnByulEyaCecrLCnewfZPgH7LnAP1zDa6Wo5Pchvo3OrH8DyFBqNuP_jYqp5_5UAnu9QG2nDTduOcxboANTlLnDrifOksiIcXqaUP7mJtQAmOFO913hqEzGDP5AHYo8AutgpsUD3B9ponzw4ofltk2_IKuu7N1qtkGaWrzWMX7VL7ULFtfxfBQnWmZ0JXeFm0ESS-uZf3kx7_UZxWZnSZg661XoQ8yDAmNEYnLDIC3Lri-q0_N9J0n7ZOeOXQhMtjbWEo-emcq2v5pS83QPjM-eFOhNSZiroLLrHstVjWvj41lPYJd32whKfKc_9oGLNVYpfUAZ1TTbhaTAjfj6mnrnEGm3qXzdmBgpcEY6Y6WoAGRXrkgXaB0_EArk0ZDwiJZsMGTPu1VBNtXbM7qKs5tEaKz5y2IMo33-Gf3myzW75euUJ9AbKR_oSBrdvwMoB.m8mpEL5E_A6Xae1N7W_Uhg/__results___files/__results___13_0.png)
![loss](https://www.kaggleusercontent.com/kf/16898899/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..ptYEf57h6fXoNWEi7lYElA.jqvd2W6OqCbvF86nu01GCnFF77pojO0gHxd-rjcrKujvgjI1L2LfaqyQ0A-YBFB7fK8CK9iDkEBrYfMwRRCr2kVw8F_KOygvRUHSWl5YsF5aCfhSMZoTxdv68_Xv_e_6g5yZDKECh8vtZBK7PFrfsCzO8id9GZe0ifs_FxwT356u5H-DHbkj370s9KCgAk5kC-_Ow6wg6XJ2EJ-I0h2sRQkdOLI1rvHUd7w297KroDb3mgo1oukgMQCURkgvJF9HWnByulEyaCecrLCnewfZPgH7LnAP1zDa6Wo5Pchvo3OrH8DyFBqNuP_jYqp5_5UAnu9QG2nDTduOcxboANTlLnDrifOksiIcXqaUP7mJtQAmOFO913hqEzGDP5AHYo8AutgpsUD3B9ponzw4ofltk2_IKuu7N1qtkGaWrzWMX7VL7ULFtfxfBQnWmZ0JXeFm0ESS-uZf3kx7_UZxWZnSZg661XoQ8yDAmNEYnLDIC3Lri-q0_N9J0n7ZOeOXQhMtjbWEo-emcq2v5pS83QPjM-eFOhNSZiroLLrHstVjWvj41lPYJd32whKfKc_9oGLNVYpfUAZ1TTbhaTAjfj6mnrnEGm3qXzdmBgpcEY6Y6WoAGRXrkgXaB0_EArk0ZDwiJZsMGTPu1VBNtXbM7qKs5tEaKz5y2IMo33-Gf3myzW75euUJ9AbKR_oSBrdvwMoB.m8mpEL5E_A6Xae1N7W_Uhg/__results___files/__results___13_1.png)

How to improve model accuracy?
1. Figure out Gradient Vanishing Problem
  -- BatchNormalization
  -- Weight_initialization
  -- activation function = 'relu'
  
2. Overfitting Problem
  -- Dropout
  
3. Global Average Pooling is better than Max Pooling
  -- Reduces parameters, make model lighter 
  -- Prevents information loss
  
Interesting Things to think
  -- Bathsize and Learning rate are **positively** correlated
  
----

## Week2 Transfer Learning

We learn about 
1. Transfer Learning 
2. Fine Tuning
3. Backbone

Homework
- Manage the image warehouse

----
## Week3 ImageNet Challenge 2014
- week2 homework review
- using python tool to handle image
- imageNet Challenge 2014
- homework3

VggNet and GoogLeNet were SOTA in 2014
the concept of main idea is to lay out layer deeper and deeper 








