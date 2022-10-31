# Malaria-detection-Model-using-Transfer-learning-VGG19

A binary image classifier that determines whether cell image contains parasite or not.Each image has been preprocessed to 224x224 pixels with a batch size of 32.
First i tried with CNN ,but it overfits so i have used vgg19 model.vgg19 is keras model that are available with predefined model weights and jst have to customize
the outer layer for better prediction,feature extraction,fine tuning.<br>

### <b>Model Architecture and summary:</b>
vgg19-->2-1-2-1-4-1-4-1-4-1-FC<br>
FC=fully connected dense layer<br>
![image](https://user-images.githubusercontent.com/68815179/198999435-a6ce3c44-17eb-47dc-a9f8-cd2fac01d8b3.png)

- Then i applied image augmenatation using ImageDatagenarator to avoid over-fitting.
- then plot the traing accuracy vs test accuracy and loss using matplotlib.
-![image](https://user-images.githubusercontent.com/68815179/199000384-14a62460-2bd0-4c25-bbd7-50c3264a64e9.png)


## Conclusion
The Architecture and parameter used in this vgg19 model are capable of producing accuracy of 95.56% on Training data,83% on validation data,on which can be further improved.<br> 
After that i have applied model using flask app which is shown below.

![image](https://user-images.githubusercontent.com/68815179/199000488-06b6fbde-5712-4d2b-8c64-82d139e1e7e7.png)
![image](https://user-images.githubusercontent.com/68815179/199000553-9902e1c1-64aa-4f1c-808c-5d9423eb1700.png)



