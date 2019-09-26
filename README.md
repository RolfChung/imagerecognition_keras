# imagerecognition_keras
image recognition with python keras on fashion data
## Summary

<p>
The goal of this project is to demonstrate the possibilities of the <a href="https://keras.io/layers/core/">Keras package</a>for image recognition. Keras is an open source deep learning library, which enables
the quick implementation of neural networks. It is a high level interface to the <a href="https://www.tensorflow.org/"> Tensorflow</a> library, a "a free and open-source software library for dataflow and differentiable programming across a range of tasks" (<a href="https://en.wikipedia.org/wiki/TensorFlow">Wikipedia</a>) developed initially by Google. The goal of the project is not 
to develop a best performing model on the Fashion MNIST data set. The number of image processes (epochs) and the 
size of the training data were restricted to decrease the run time and computational intensity and deliver results quickly.
</p> 

<p>
According to <a href="https://research.zalando.com/welcome/mission/research-projects/fashion-mnist/">Zalando Research</a> the "Fashion-MNIST is a dataset of Zalando’s article images consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28×28 grayscale image, associated with a label from 10 classes." Nowadays it is deemed to easy as to work as a deep learning challenge, but it remains a good
starting point to demonstrate the workflow and functionality of the Keras library.
</p> 

<p>
This project in applies the full basic Keras workflow to the data set. These methods are
applied:
</p>

<ul>
<li><b>Import</b></li>  
<li>installing and importing Tensorflow and Keras</li>
<li>data import</li>
<li><b>Preparing some tools and methods</b></li> 
<li>representing images with data</li>
<li>turning 3d color images into 2d gray images</li>
<li>one-hot-encoding by writing code</li>
<li>encoding using sklearn</li>
<li>encoding using keras</li>    
<li>clarify the principle of evaluation (of a classifier)</li>    
<li><b>Modeling a sample of the Fashion MNIST data set
</b></li>   
<li> Taking a random sample of the fashion dataset</li>    
<li> Model the sample data with sequential Convolutional Neural Networks (CNN)</li>    
<li>Calculating simple convolutions by coding</li>    
<li>Determining one dimensional convolutions</li>
<li>Determining two dimensional convolutions</li>
<li>Creating different kernels</li>
<li>Determining convolutions using keras</li>
<li>Tuning the parameters of the keras model</li>
<li>Creating a deep learning convolutional network</li>
<li>Convolution layers</li>
<li>Comparing the number of parmeters of a convolutional and dense network</li>
<li>Flatten layers</li>
<li>Pooling layers</li>
<li>Observing learning performance</li>
<li>Callbacks</li>
<li>Regularization</li>
<li>Dropout layer</li>
<li>BatchNormalization</li>
<li><b>Model the complete data set as a sequential Convolutional Neural Network (CNN)</b></li>
</ul>

<p>
Comments are and explanations are given within the coding.
</p> 
