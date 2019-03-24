# Digit_recognizer
Using CNN, LeNet, AlexNet as backbone network and apply mixup to compare.
## Result
Training set : Testing set = 4:1

MNIST dataset come from Kaggle competition.

|    Alpha    |    CNN    |    LeNet    |    Alexnet    |
|-------------|:---------:|:-----------:|--------------:|
|      0      |   98.631  |    97.631   |    98.821     |
|     0.1     |   99.024  |    98.524   |    98.440     |
|     0.2     |   98.964  |    98.262   |    98.774     |
|     0.4     |   99.060  |    98.464   |    99.000     |
|     0.8     |   98.857  |    98.476   |    98.952     |
## Run
Just run the notebook, require Pytorch.
You can add alpha=0 to the mixup notebooks so you don't need to run the original ones. I still put the original ones on for someone who don't want to use mixup.
## Acknowledgements
