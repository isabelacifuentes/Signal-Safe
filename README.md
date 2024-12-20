# SignalSafe



<img src="SignalSafeLogo.png" alt="SignalSafe Logo" width="600"/>

[Introduction](https://docs.google.com/presentation/d/131DjNkodW-H4hMsFSn5oTiVO1D9MgEXv0WWQGfe7uTA/edit#slide=id.p)
#
#








###
[Data Deck](https://docs.google.com/presentation/d/1BwfaCczKoyCVFjTcvxK5QguIIY-9vJnExXco0d_DtjQ/edit#slide=id.g2d5f33bc7f1_0_196)

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/Modern_British_LED_Traffic_Light.jpg/440px-Modern_British_LED_Traffic_Light.jpg" alt="red" width="250"/>

<img src="https://hips.hearstapps.com/hmg-prod/images/green-traffic-light-royalty-free-image-1675887049.jpg" alt="green" width="250"/>



#
#


###

[Website](https://isabelacifuentes.github.io/Signal-Safe/)



##

##

[Youtube Video](https://youtu.be/0hLI2-J7s10)


##

##
<img src="https://cdn-5f733ed3c1ac190fbc56ef88.closte.com/wp-content/uploads/2017/03/alexnet_small.png" width="400">

**Alexnet Convents**

AlexNet is a convolutional neural network designed for image classification. It processes input images through convolutional layers to extract features, applies activation functions for non-linearity, uses pooling for spatial reduction, and employs fully connected layers for predictions


##

##
<img src="https://miro.medium.com/v2/resize:fit:1248/1*ECIusCMDF0J9ONrGmG-BBg.png" width="400">

**Alexnet Pooling**

Pooling is an essential operation in convolutional neural networks (CNNs) like AlexNet, which reduces the spatial dimensions of feature maps while retaining important features. Pooling helps in: Reducing computational complexity, preventing overfitting by reducing the parameters and ensuring translational invariance.



##

##

![image](https://github.com/user-attachments/assets/61996ba4-3379-4894-a011-de51d219cc48)


**Alexnet Activation Functions**

Activation functions introduce non-linearity into neural networks, enabling them to learn complex patterns and relationships in the data. In AlexNet, the Rectified Linear Unit (ReLU) activation function is used extensively

The ReLU function is defined as:

𝑓(𝑥)=max(0,𝑥)

Output:
If x>0, output x.
If x≤0, output 0.



##

##

**Fully Connected Layers in AlexNet**

The Fully Connected (FC) layers in AlexNet are part of the classifier section of the network. 

These layers:
- Combine features learned by earlier layers to make final predictions.
- Perform high-level reasoning by mapping feature maps to output classes.

Fully connected layers are expressed as: y=Wx+b

x: Input feature vector.
W: Weight matrix.
b: Bias vector.
y: Output vector.



##

##

![image](https://github.com/user-attachments/assets/d4b58f5f-3f07-4f22-a392-192d4471b845)

**Loss Function in AlexNet**

The loss function measures how well the model's predictions match the actual labels. In AlexNet, a classification task, the most commonly used loss function is the Cross-Entropy Loss, which is suitable for multi-class or binary classification.

