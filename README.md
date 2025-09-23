# DL-Convolutional Deep Neural Network for Image Classification
### NAME: EZHIL NEVEDHA K
### REG.NO: 212223230055
## AIM
To develop a convolutional neural network (CNN) classification model for the given dataset.

## THEORY
The MNIST dataset consists of 70,000 grayscale images of handwritten digits (0-9), each of size 28×28 pixels. The task is to classify these images into their respective digit categories. CNNs are particularly well-suited for image classification tasks as they can automatically learn spatial hierarchies of features through convolutional layers, pooling layers, and fully connected layers.

## Neural Network Model
Include the neural network model diagram.

## DESIGN STEPS
### STEP 1: 

Write your own steps

### STEP 2: 



### STEP 3: 



### STEP 4: 



### STEP 5: 



### STEP 6: 





## PROGRAM

### Name:

### Register Number:

```python
class CNNClassifier(nn.Module):
    def __init__(self, input_size):
        super(CNNClassifier, self).__init__()
        #Include your code here

    def forward(self, x):
        #Include your code here



# Initialize the Model, Loss Function, and Optimizer
model =
criterion =
optimizer =

def train_model(model, train_loadr, num_epochs=10):
    #Include your code here

```

### OUTPUT

## Training Loss per Epoch

<img width="463" height="233" alt="image" src="https://github.com/user-attachments/assets/e360ea92-a4d8-4bd4-865f-29fa27116307" />


## Confusion Matrix

<img width="681" height="600" alt="image" src="https://github.com/user-attachments/assets/bda38cc1-6824-4cd6-9142-0c5d5d2ea3c9" />


## Classification Report
<img width="470" height="326" alt="image" src="https://github.com/user-attachments/assets/3588e5a3-35c8-4d69-a316-78e40d1ca0c1" />


### New Sample Data Prediction
<img width="441" height="432" alt="image" src="https://github.com/user-attachments/assets/ff6a8ab1-6afb-4886-bbf5-789c582065ef" />


## RESULT
Thus, CNN model has been developed
