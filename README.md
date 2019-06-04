# Neural-Networks-in-R

### NOTES: 
1) There are 2 notebooks here. I created both these notebooks on Google Colab. Google had experimented with the use of IR Kernel for a while on Colab. I feel Colab is the one of the best platforms for Machine Learning Tasks. 

2) _RStudio_ has come up with "Keras" package for R. The interface of R's Keras is similar to Python's Keras. I have attempted to solve some basic deep learning tasks in R using Keras.  To use Keras within R, Tensorflow(R version) has to be installed. And for this purpose, the python virutal environment has to be created witin R. I have mentioned all these steps in the Notebooks.

### NOTEBOOKS:

#### ~R_auto_encoder

In this notebook, I have tried to simulate a simple _AutoEncoder_ to capture the patterns in MNIST dataset. The Dataset can be obtained from within Keras. Even Colab provides a miniature version of the datatset to work with. The autoencoder in my notebook works good.

#### ~Convolutional_Network_in_R

In this notebook, I have worked with the CIFAR datset (basically the smaller version cifar10). Firstly, I have used a small CNN model. I have mentioned the architecture of the model. This model was about 67% accurate ( which is good for my 1st deep learning model in R) but unsatisfactory. So, I resorted to Transfer Learning. I used VGG16 Model with predefined weights(of imagenet). The Input Layer and the Output block had to be changed to make the model work with the cifar10 dataset. After a bit if fine=tuning the model, prediction accuracy was about 90% (a good improvement).


#### Observations

During the course of creating these notebooks, I found that using Keras with R is as swift ( and very similar to ) as that in Python. But for using Keras in R, some steps are required to be followed. 

In case of Deep Learning, Python is a bit faster than R and more robust, but R is as efficient and reliable as Python with regard to Deep Learning Projects.

~Sumit Bhattacharya
