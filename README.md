# Image_Captioning_RNN
Image Captioning using Flickr8k Dataset

Although I have used subset of the dataset for training, the full dataset can be downloaded from [here](https://www.kaggle.com/shadabhussain/flickr8k "Flickr8k Dataset").

For extracting features from images VGG16 model is used. 
These features are stores in .pkl file. 
The captions are pre-processed and mapped with images. 
LSTM is used for generating sequence of words (captions) given the extracted features of the images.
