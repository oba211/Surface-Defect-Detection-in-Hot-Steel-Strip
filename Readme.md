INTRODUCTION-

Hot-rolled steel strip, is products of iron and steel industry, is mostly used in automotive, electrical, chemical, shipbuilding and other industries, and has a great development space in the next few years. In hot-rolled steel strip apparent quality is an important factor affecting its performance. Because of influence of equipment, raw materials and manufacturing technology, different types of irregularities on the surface of hot-rolled steel strip are formed in the production process, such as patches, crazing and inclusion. These defects do not affect the apparent quality of steel products, and are easy to cause rust, stress concentration, cracking and other quality problems, which greatly reduces the performance and service life of steel products. At present, manual inspection is the main method to detect the surface defects on hot-rolled steel strip in industry. This process is not only lengthy and laborious, but also high error rate. With the continuous development of image processing technology, machine learning method has gradually replaced the traditional method of manual detection, and has been applied in large-scale production practice.


TECHNOLOGY USED IN PROJECT-

1 Programmimg Language -Python

2 Python Library-Os,Numpy,Pandas,Matplotlib,keras,tensorflow

2 Machine Learning-Supervised-Machine learning

3 Data Type-categorical

3 Deep learnig-CNN Neural network

4 IDE-Anaconda Navigator-Jupyter Notebook

5 Data Set-http://faculty.neu.edu.cn/yunhyan/NEU_surface_defect_database.html#:~:text=In%20the%20Northeastern%20University%20(NEU,)%20and%20scratches%20(Sc).


ABOUT DATASET-

This dataset was downloaded from NEU Metal Surface Defects Databse which contains six kinds of typical surface defects of the hot-rolled steel strip are collected, i.e., rolled-in scale (RS), patches (Pa), crazing (Cr), pitted surface (PS), inclusion (In) and scratches (Sc). The database includes 1,800 grayscale images: 300 samples each of six different kinds of typical surface defects.

But for this analysis, the dataset divided into 3 directories. The training directory contains 276 images of each class from the 300 images. The rest 24 images of each class also divided into tests and valid datasets.


PARAMETERS-


rescale=1. / 255,
shear_range=0.2,
zoom_range=0.2,
horizontal_flip=True

To stop training a neural-network using callback-98%

Activation Function=relu

optimizer-'rmsprop'

batch_size = 32

epochs=20

Activation Function-
                    1 Rectified Linear Unit (ReLU) Function
                    2 Softmax Function


OPTIMIZER-

Optimizers are algorithms or methods used to change the attributes of your neural network such as weights and learning rate in order to reduce the losses.

RMSprop Optimizer

RMSprop is a gradient-based optimization technique used in training neural networks. It was proposed by the father of back-propagation, Geoffrey Hinton. Gradients of very complex functions like neural networks have a tendency to either vanish or explode as the data propagates through the function (refer to vanishing gradients problem). Rmsprop was developed as a stochastic technique for mini-batch learning.

RMSprop deals with the above issue by using a moving average of squared gradients to normalize the gradient. This normalization balances the step size (momentum), decreasing the step for large gradients to avoid exploding and increasing the step for small gradients to avoid vanishing.

Simply put, RMSprop uses an adaptive learning rate instead of treating the learning rate as a hyperparameter. This means that the learning rate changes over time.


