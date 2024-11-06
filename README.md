# Art Authentication: A Comparative Analysis of Convolutional Neural Network (CNN) Architectures for Detecting AI-Generated and Human-made Digital Artworks (Thesis)

### Prototype link
A prototype of the study, Try it out [here](https://github.com/Hchama/ThesisPrototype).

### Dataset
sample batch of the dataset

![batch](https://github.com/user-attachments/assets/b3781c7a-b2ef-4b73-bff0-35980302e16c)

### Training Results
Evaluation metrics for training, training stopped at epoch 1 due to a EarlyStoppingCallback function which stops the training when there is no improvements in the loss function after 5 iterations.
![ft2](https://github.com/user-attachments/assets/a2a262ea-55e9-4e66-9f68-50f82a80b4d4)

Confusion Matrix

![ft1](https://github.com/user-attachments/assets/30a3fe6e-7c10-4bf9-982d-37fa04ce61b5)

### Heatmap
Here is a heatmap that indicates where the model looks when it is validating whether an image is AI or not. The hotter areas means that the AI focuses more on that part to determine whether an artwork was AI or not and the opposite for colder areas.

Human made artwork

![ft4](https://github.com/user-attachments/assets/baebe12c-7cd8-4305-bf15-d093acf9f8f0)

AI generated artwork

![ft3](https://github.com/user-attachments/assets/a984234f-fa34-4c19-9db1-f10a85ce48c9)

### Metrics
Accuracy: 0.8452380952380952

precision: 0.8043478260869565

recall: 0.9024390243902439

f1_score: 0.8505747126436782
