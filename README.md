# Malaria-detection-Model-using-Transfer-learning-VGG19

A binary image classifier that determines whether cell image contains parasite or not.Each image has been preprocessed to 224x224 pixels with a batch size of 32.
First i tried with CNN ,but it overfits so i have used vgg19 model.vgg19 is keras model that are available with predefined model weights and jst have to customize
the outer layer for better prediction,feature extraction,fine tuning.<br>

### <b>Model Architecture and summary:</b>
vgg19-->2-1-2-1-4-1-4-1-4-1-FC<br>
FC=fully connected dense layer
![image](https://user-images.githubusercontent.com/68815179/198999435-a6ce3c44-17eb-47dc-a9f8-cd2fac01d8b3.png)


