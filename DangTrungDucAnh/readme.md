# Image classification
## Overview
Because of not having much data, I use transfer learning form VGG16 model to define my model. I replaces 3 last layers of VGG16 by 3 dense layers and set they trainable. After 5 train epochs, my model get 0.90% top 1 accuracy and 0.97 top 3 accuracy on validation set. 
## Running
You don't have to install anything to your computer.
You can up load your dataset to Google Drive and run this code in Google Colab.
First, you must run Load_data.ipynb file to generate data.npy and lable.npy file from image dataset.
Then, you run Dogcnn.ipynb

 
