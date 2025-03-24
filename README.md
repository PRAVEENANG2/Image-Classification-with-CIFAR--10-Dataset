# Image-Classification-with-CIFAR--10-Dataset

INTRODUCTION:

A dataset of 60,000 32*32 color images in 10 classes, with 6,000 images per class.

50,000 training images and 10,000 test images.

Widely used for image classification tasks and benchmarking machine learning models.

CLASS NAMES:

List the 10 classes (Airplane ,automobile,bird,cat,deer,dog,frog,horse,ship,truck).

Data Exploration and Preprocessing:

Data Loading:

Mention loading the CIFAR-10 dataset using tf.keras.datasets.cifar-10.load_data().

Data visulization:

Include a few sample images from each class (using plot_images function from your code).

show the distribution of labels in the training dataset (using sns.countplot).

Data Preprocessing:

Normalize Pixel Values to the range ( 0, 1 ).

one-hot encode the labels (if used).

MODEL ARCHITECTURES:

CNN FROM SCRATCH:

Describe the architecture of your custom-built cnn model (number of layers,activation function ,etc).

PRE-TRAINED MODELS:

Introduce VGG16,Resnet50, and Mobilenetv2.

Mention the concept of transfer learning and fine-tuning.

TRAINING AND EVALUATION:

Traning Process:

Describe how you trained each model(optimizer,loss,function,epochs,batch size).

Explain the use of validation data for monitorimg performance.

Evaluation metrics:

Focus on accuarcy as the primary metric.

Include a table or bar graph comparing the test accuraies of different models(using plot_bar_graph function from your code).






![Slide1-2](https://github.com/user-attachments/assets/6fd8f5cc-e853-4d91-aa88-228d02b160bf)







  
