# Transfer-learning-using-CNN
Different CNN flavors like VGG, ResNet, DenseNet, SqueezeNet, Inception and Xception used to gain knowledge of already trained models for image classification problem.

- Transfer Learning: Transfer learning is the improvement of learning in a new task through the transfer of knowledge from a related task that has already been learned.

- Frozen Model:  Only last 3 to 4 layers are trained on latest dataset, previous layers of the model is freezed.Layer freezing means that the layer weights of the trained model do not change when reused on a subsequent downstream mission, they remain frozen.
Basically, when backpropagation is performed during training, these layer weights aren't compromised.

- Finetuned Model: only top layers of the base model is trained on new data to fine-tune the higher-order features in base model to make it relevant to specific task.

Models
- VGG: VGG is a CNN model designed by Oxford’s Visual Geometry Group (VGG) for large-scale image recognition. VGG has two flavors: VGG16 and VGG19. 
The only difference between VGG19 and VGG16 is the last 3 convolution blocks that have 4 convolutional layers in VGG19 and 3 convolutional layers in VGG16.  

- ResNet: Residual Neural Network (ResNet) is a convolutional neural network that can train a large number of layers with compelling performance. 
ResNet has many flavors like ResNet-50, ResNet-101 and ResNet-152. ResNet-V2 differs from ResNet-V1 because it uses batch normalization before each weight layer.

- DenseNet: In Dense Convolutional Neural Network (DenseNet), every layer is connected with all preceding layers and feature maps of previous layers are used as input
to the new layer and its feature map is used as input for succeeding layer while traditional convolutional networks have a direct connection between layers and features of previous layers not provided to the next layer. DenseNet has many flavors like DenseNet-121, DenseNet-169, and DenseNet-201.

- Inception: Inception is a deep neural network designed by Google that plays an important role in the development of convolutional network classifiers. 
The inception has many variants like Inception-v1, Inception-v2, Inception- v3 and Inception Resnet-v2.

- Xception: Xception (extreme version of Inception) is a deep neural network designed by Google. Xception model modifies depth-wise separable convolution of inception model which implement 1 × 1 convolution before channel-wise spatial convolution.
The Xception network has 71 layers designed for large scale image recognition. Since the Xception architecture has the same number of parameters as Inception V3, the performance gains are not due to increased capacity but rather to more 
efficient use of model parameters.

- SqueezeNet: SqueezeNet is a small neural network with 18 layers that can fit into a small amount of memory and requires less bandwidth over a computer network. 
SqueezeNet has 50× fewer model parameters than AlexNet but achieves AlexNet-level accuracy. 




- Using Transfer learning techniques on Image Classification task i.e Malaria detection achieve above 93% accuracy for all models 
