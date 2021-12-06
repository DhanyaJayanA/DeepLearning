### DeepLearning
Deep learning is a subset of machine learning (ML), where artificial neural networks—algorithms modeled to work like the human brain—learn from large amounts of data.

**Types of neural networks in deep learning**

        1. Artificial Neural Networks (ANN)
        2. Convolution Neural Networks (CNN)
        3. Recurrent Neural Networks (RNN)

#### Image Classification:  
  Predict the type or class of an object in an image.
  
  Input: An image with a single object.
  
  Output: A class label (e.g. one or more integers that are mapped to class labels)

**Types:**

  1. **Binary Classification** - binary output, binary_crossentropy loss and sigmoid activation function.
  
  2. **Multi Classification** - more than two output, categorical_crossentropy loss and softmax activation function.
  
     1. MultiClassification using CNN. <a href="https://github.com/DhanyaJayanA/DeepLearning/blob/main/MultiClassification_CNN.ipynb">Code</a>
   
     2. ButterflyClassification using transfer learning MobileNetV2. <a href="https://github.com/DhanyaJayanA/DeepLearning/blob/main/butterflyclassification.ipynb">Code</a>
     
  3. **Multilabel Classification** - more than one label for a single image,  binary_crossentropy loss and  sigmoid activation function.
  
     1. multilabelclassification. <a href="https://github.com/DhanyaJayanA/DeepLearning/blob/main/multilabelclassification.ipynb">Code</a>
  
     2. human-protein-atlas-image-classification. <a href="https://github.com/DhanyaJayanA/DeepLearning/blob/main/human-protein-atlas-image-classification.ipynb">Code</a>

#### Object Localization: 
  Locate the presence of objects in an image and indicate their location with a bounding box.
  
  Input: An image with one or more objects.
  
  Output: One or more bounding boxes (e.g. defined by a point, width, and height).
  
  Bounding Box. <a href="https://github.com/DhanyaJayanA/DeepLearning/blob/main/BoundingBox.ipynb">Code</a>
  

#### Transfer Learning: 
  Transfer learning is the method of starting with a pre-trained model and training it for a new — related — problem domain.
