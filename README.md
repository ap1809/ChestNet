# Pneumonia Detection
### What is Pneumonia
![pneumoniag1042128216_1504073 (2)](https://github.com/ap1809/ChestNet/assets/73573200/9d87f9c1-ecd7-4756-b557-fb6ebe766873)

Pneumonia is an inflammatory lung condition affecting primarily the tiny air sacs known as alveoli. Symptoms typically include some combination of productive or dry cough, chest pain, fever, and difficulty breathing. The severity of the condition is variable. 
Pneumonia is usually caused by infection with viruses or bacteria and less commonly by other microorganisms, certain medications, or conditions such as autoimmune diseases. Risk factors include cystic fibrosis, chronic obstructive pulmonary disease (COPD), asthma, diabetes, heart failure, a history of smoking, a poor ability to cough such as following a stroke, and a weak immune system. Diagnosis is often based on symptoms and physical examination. Chest X-ray, blood tests, and sputum culture may help confirm the diagnosis. The disease may be classified by where it was acquired, such as community- or hospital-acquired or healthcare-associated pneumonia.

## DATASET
  kaggle: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

# Classification Using CNN

## CNN

![download](https://github.com/ap1809/ChestNet/assets/73573200/d170e3a0-e26c-4e4a-bf7c-7b2917b0717a)

CNN stands for Convolutional Neural Network, which is a type of deep learning algorithm commonly used for image and video processing tasks. CNNs are designed to automatically learn and extract relevant features from input images and classify them into different categories.

The basic architecture of a CNN consists of several layers, including convolutional layers, pooling layers, and fully connected layers. In the convolutional layer, a set of learnable filters are applied to the input image to produce a feature map, which captures the presence of specific features such as edges, lines, and textures. The pooling layer then reduces the spatial size of the feature map by down-sampling, which helps to reduce the computational cost and prevent overfitting.

The output of the pooling layer is fed into the fully connected layer, which performs the classification task. The fully connected layer consists of several neurons, each representing a different class label, and uses a softmax function to compute the probabilities of each class.

During the training phase, the weights of the filters in the convolutional layers and the neurons in the fully connected layers are optimized through a process called backpropagation, which involves computing the gradient of the loss function with respect to the weights and updating them using an optimization algorithm such as stochastic gradient descent (SGD).

CNNs have achieved state-of-the-art performance in many computer vision tasks, such as image classification, object detection, and semantic segmentation. They are widely used in various applications, such as autonomous driving, medical imaging, and facial recognition.


  

