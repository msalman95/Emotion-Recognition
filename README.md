# Emotion-Recognition using Center Loss and Softmax Loss

Center Loss was introduced in this paper: Wen et al. A Discriminative Feature Learning Approach for Deep Face Recognition. ECCV 2016.
Github link: https://github.com/KaiyangZhou/pytorch-center-loss

#How to Get Started
First Download the CK+ dataset - https://www.kaggle.com/shawon10/ckplus
and put the images in "data" folder.

#Dataset
The dataset CK+ contains 981 images of size 48x48x3. The dataset contains the following emotions: Anger, Contempt, Disgust, Fear, Happy, Sadness, Surprise. 

The whole code is provided in Emotion.ipynb. It splits the data into train (80%) and test (20%) and trains a 6 layer CNN with both Softmax and Center Loss. The notebook also contains the network with just 2-dimensional features to show the robustness and learning of Center loss as compared to Softmax Loss.

#Requirements
NVIDIA GPU
Pytorch 1 or above
SKLearn, Numpy, Matplotlib

#How to Run
After downloading the whole dataset and putting it in data directory, run the ipynb notebook to train and test your model.
