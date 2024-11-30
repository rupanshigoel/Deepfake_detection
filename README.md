# Deepfake_detection<br/>
The project aims to detect deepfake videos using deep learning techniques like ResNext and LSTM. It uses a Res-Net Convolution Neural Network to extract frame level features which are then used to train a Long short Term Memory (LTSM) based Recurrent Neural Network (RNN) to clasify whether the video is an orginal or deepfake.<br/>
# Prepocessing<br/>
  Load the dataset<br/>
  Split the video into frames<br/>
  crop the face from each frame<br/>
  save the face cropped video<br/>
# Model and Training<br/>
  It will load the preprocessed video and labels from a csv file<br/>
  Create a pytorch model using transfer learning with RestNext50 and LSTM<br/>
  Split the data into train and test data<br/>
  Train the model<br/>
  Test the model<br/>
  save the model in .pt file<br/>
# Predicting<br/>
  Load the saved pytorch model<br/>
  Predict the output based in trained weights.

# Datasets:
  https://github.com/ondyari/FaceForensics<br/>
  https://github.com/yuezunli/celeb-deepfakeforensics<br/>
  https://www.kaggle.com/c/deepfake-detection-challenge/data<br/>
