# SimpleCV - 2023 Fellowship.ai Computer Vision Challenge

Code Challenge submission for the 2023 Fellowship.ai Cohort 26 application.

Apply a pre-trained ResNet50 model to the Flowers Dataset: https://www.robots.ox.ac.uk/~vgg/data/flowers/102/

Some tutorials and links that helped me:

Basic Pytorch Tutorial on Transfer Learning: https://pytorch.org/tutorials/beginner/transfer_learning_tutorial.html

Kaggle Review on Models classifying Flowers 102 Dataset: https://www.kaggle.com/c/oxford-102-flower-pytorch

There was another repo that I studied: https://github.com/intsco/udacity-fb-pytorch-project (I used the same data and labels as them).

While they were able to achieve 97%-99.5% test accuracy using trained ResNet101/ResNet34 models using 5 fold cross validation, they had modified the ResNet architecture and had more powerful GPUs available (Tesla K80s). I was able to achieve a 59% test accuracy using a manual split and used one of Google Colab's T4 Tensor GPUs which is slightly weaker than a K80.   
