# 物連網Lesson 12 Pytorch Basis

## 深度學習
學習資源： [台北科技大學 黃嘉千](https://github.com/taipeitechmmslab/MMSLAB-TF2)

1. mnist 手寫辨認 ANN/DNN (MLP)
2. CNN
3. cifarlo(彩色) LeNet
4. Transfer Learning
5. GAN AE

## 高階訓練技巧
### kears
1. 調參數 (learning rate、batchsize)  
   (autobatch:依記憶體大小自動決定batchsize)
2. [dropout](https://www.educba.com/pytorch-dropout/)
3. [L1/L2 Regularization (Lasso)](https://github.com/poojamahajan0712/medium_blog/blob/master/regularisation/MNIST_with_L1_%26_L2_Regularisation.ipynb)
4.  [Early stopping to avoid overfitting (Callback function)](https://stackoverflow.com/questions/71998978/early-stopping-in-pytorch)
5. [Batch Normalization](https://github.com/christianversloot/machine-learning-articles/blob/main/batch-normalization-with-pytorch.md)
6. tensor board
7. 把比較好的 model 存起來 >> pickle H5

### torch
參考資料 ：⾹港科技⼤学 PyTorch 四⽇速成教程
【⾹港科技⼤學PyTorch四⽇速成教程】「PyTorchZeroToAll」 by Sung Kim
GitHub:https://github.com/hunkim/PyTorchZeroToAll
Slides:https://drive.google.com/drive/folders/0B41Zbb4c8HVyUndGdGdJSXd5d3M
Youtube: • Youtube https://www.pytorchtutorial.com/goto/http://bit.ly/PyTorchVideo

## Deep Learning 3 大框架
![](https://i.imgur.com/sX2maVH.png)

## code 講解
### pytorch CNN
#### pytorch 需自行將model 用 .to(device) 才能用 GPU跑
#### model 會呼叫 forward function
![](https://i.imgur.com/6cnYFEr.jpg)
![](https://i.imgur.com/t1eLcgd.jpg)
#### nn.linear
![](https://i.imgur.com/Y3ZTuDQ.jpg)
![](https://i.imgur.com/BqdX3UW.jpg)



### Lecture_12_Pytorch四日速成練習.ipynb
#### loss backward()
![](https://i.imgur.com/Vb4z93u.jpg)
![](https://i.imgur.com/spLJFMP.jpg)

#### detach tensor to numpy
![](https://i.imgur.com/JslR3iK.jpg)
