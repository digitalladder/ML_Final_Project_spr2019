## Image Generator
Using GAN (Generative Adversarial Networks), generate simulated picture based on given condition. The G's(generator) training goal is to deceive the D(discriminators) to make D believe that the fake image is match to the condition.


[Code](https://github.com/digitalladder/ML_Project_2019/blob/master/ImageTranslation/ImageGenerator_GPU.ipynb)

First generated picture with poor acc value

![](https://github.com/digitalladder/ML_Project_2019/blob/master/ImageTranslation/images/facades/0_0.png)

picture generated after 22 epoch training

![](https://github.com/digitalladder/ML_Project_2019/blob/master/ImageTranslation/images/facades/20_200.png)

picture generated after 100 epoch

![](https://github.com/digitalladder/ML_Project_2019/blob/master/ImageTranslation/images/facades/99_0.png)

[reference paper](https://arxiv.org/abs/1611.07004)

data loader is based on the follow link

[data loader](https://github.com/eriklindernoren/Keras-GAN/blob/master/pix2pix/data_loader.py)