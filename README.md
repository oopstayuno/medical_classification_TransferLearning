# medical_classification_TransferLearning

About Data:

Total Data Size = 559

Nos. of classes: 3 [‘Allergic Eczema’, ‘Chickenpox’, ‘Cellulitis’]

Total Data Size w,r,t each classes:

| Classes         | Dataset Size  |
| --------------- | ------------- |
| Allergic Eczema |      273      |
|    Chickenpox   |      141      |
|    Cellulitis   |      145      |

Dimension: varying from 160x168 to 1000x1000 pixels
Has been resized to similar dimensions with respect to models used.


Algorithm:
Convolution Neural Network is used for image classification. As CNN itself acts as feature extractor and feature selection CNN becomes the ideal choice for selecting CNN.

Transfer Learning is used for training the model while fine tuning the footers.

CNN Architecture used:  Xception, VGG16, ResNet50, InceptionV3

Comparison Table for each model:

|    Base Model  | Training Loss | Training Accuracy  | Test Loss | Test Accuracy |
| -------------- | ------------- | ------------  | -------------- | ------------- | 
| Xception Model | 0.2405        |  0.9016       | 0.8732         | 0.6339        |
| InceptionV3    | 0.4349        |  0.8209       |  0.943         | 0.6339        |
| ResNet         | 0.2511        |  0.924        | 2.1066         | 0.491         |
| Vgg16          | 0.1047        |  0.9642       | 1.2529         | 0.7232        |
