# Digit_recognizer
Using CNN, LeNet, AlexNet as backbone network and apply `mixup` to improve and compare.
## Result
* Training set : Testing set = 4:1, separated from `train.csv`.
* MNIST dataset come from [Kaggle competition](https://www.kaggle.com/c/digit-recognizer).
* Alpha=0 means not using mixup
* For LeNet, changing alpha from 0 to 0.1, accuracy improved 0.9%!

|    Alpha    |     CNN     |    LeNet    |    Alexnet    |
|-------------|:-----------:|:-----------:|--------------:|
|      0      |    98.631   |    97.631   |    98.821     |
|     0.1     |    99.024   |    98.524   |    98.440     |
|     0.2     |    98.964   |    98.262   |    98.774     |
|     0.4     |    99.060   |    98.464   |    99.000     |
|     0.8     |    98.857   |    98.476   |    98.952     |
## Run
Just run the notebook, require Pytorch.

You can add `alpha=0` to the mixup notebooks so you don't need to run the original ones. 

I still put the original ones on for someone who don't want to use mixup.

* You may choose the GPU version `CNN_GPU`
## Mixup
[mixup: Beyond Empirical Risk Minimization](https://arxiv.org/abs/1710.09412)
