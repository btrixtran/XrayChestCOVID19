Based on DarkCovidNet classifier which implemented for the you only look once (YOLO) real time object detection system. 
Our model consist of 21 layers and 6 pooling layer. The structure is as below where C stands for the convolutional layer and M stands for pooling layer. We starts with C1 as input layer number 1
C1-M1-C2-M2-C3-C4-C5-M3-C6-C7-C8-C9-C10-M4-C11-C12-C13-M5-C14-C15-C16-C17-C18-M6-C19-C20-C21
We use Layer Normalization to normalize the feature and PReLU for activation function
We use Maxpool method for pooling and Adam optimizer for weight updates, and binary cross-entropy as loss function
The training is run for 50 to 100 epochs with learning rate of 0.001 and 0.0001

