## DL-Project-Face-Mask-Detection

 ## Mask Classifier

 Coronavirus has now become the talk of the town, Like most people in the world right now are suffering badly and everyday thousand's of people are dying because of COVID-19, I’m genuinely concerned about them. So, Instead of sitting idle and let negative thoughts grow day by day,I decided to do what I do best .In the above project i used webscrapped data with classes people wearing mask and no mask and trained a resent 50. then i used the model to predict on a webcam feed

# Installation:

 All the required installation are mentioned in the requirements.txt

# Usage:

 Step 1:training the model with the appropriate data with training.ipynb, downloading the model weights.

 Step 2:add the model weight in label.py program and execute it.

 Step 3:finally run webcam.py, the webcam output gets saved as out.mp4.

# Features

1) Trainable classification model (MobileNetV2/ResNet/Custom CNN)

2) Data augmentation for robustness (flip, rotation, brightness, zoom)

3) Evaluation metrics: accuracy, precision, recall, F1, confusion matrix

4) Inference on images, videos, and webcam stream with bounding boxes

5) Export model for deployment (.pt, ONNX)

# Training

1) Important hyperparameters to tune:

2) batch_size (16–64 depending on GPU memory)

3) learning_rate (1e-4 to 1e-2, use schedulers)

4) optimizer (Adam/SGD + momentum)

5) weight decay / dropout to reduce overfitting

6) image size (224 or 256 for pretrained backbones)

Checkpointing: train.py should save the best model by validation F1 or accuracy.
