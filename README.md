# Human-Action-Recognition
## Using keras for building models to predict human action in videos using ucf101 dataset

## Using ucf101 dataset built two models to classify 101 human actions in videos

## I got train accuracy of ~97% and validation  of ~92% for both approached, there's an overfitting despite using dropout but we still can do better by using data augmentation or other regulations methods. And we might choose different models for extracting features and we might fine-tune some layers of them

## Main files:

- "extract features.ipynb", read videos and use pre-trained vgg16 to extract features from each frame
- "build_model-lstm.ipynb", building lstm model based on features extracted using vgg16 
- "build_model-cnn.ipynb", building cnn model based on features extracted using vgg16 


