# road-classification
 This project contains my code, dataset and the pre-trained model of my bachelor degree project.

# ABSTRACT
This graduation project focuses on the working environment classification problem of mobile robots with a wide range of application scenarios and rapid development momentum and analyzes the conventional machine learning methods. Contrapose to the disadvantages of the need for manual extraction of features, it chooses the excellent convolutional neural network method which shines in the field of image classification, and this method can be learned in iterative training and automatically extract features.

This thesis presents a method of rapid expansion of image data, "Cycle-Cut Method", which effectively solves the problem of being lack of training samples. It produces 10 types of topographic data sets including cement, asphalt, grassland and so on, which fills the gaps in the dataset of the field and facilitates learning from each other. Through deep learning framework TensorFlow, a terrain classification model “billow-8 net” is designed and constructed. This model includes 5 convolution/pooling layers, 2 full-connections layers and 1 softmax layer, achieving 98% accuracy.

During the training process, the model parameters are saved and can be used at any time without having to be re-trained in the future. This process makes it possible to use them for practical applications on mobile robots.

# Key words：Terrain environment classification；Machine learning；Convolution neural network；TensorFlow
 
