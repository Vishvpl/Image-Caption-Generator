This project implements an Image Caption Generator model that generates natural language descriptions for images. It leverages a Convolutional Neural Network (CNN) for feature extraction from images and a Long Short-Term Memory (LSTM) network for generating coherent captions based on the extracted features.
<br><b>Key Features:</b><br>
<ol><li><b>Image Preprocessing:</b> The images are resized and preprocessed to feed into the InceptionV3 model.</li>
<li><b>Feature Extraction:</b> InceptionV3, pre-trained on the ImageNet dataset, is used to extract high-level features from the images.</li>
<li><b>Text Preprocessing:</b> Captions are tokenized, cleaned, and padded for input into the LSTM model.</li>
<li><b>Caption Generation:</b> An LSTM model is trained to generate captions by learning to predict the next word in the sequence based on the image features and previous words.</li></ol>
<b>How to Run:</b>
<ol><li>Clone the repository.</li>

<li>Install the required dependencies.</li>

<li>Download the Flickr8k dataset and store it in the specified directory.</li>

<li>Run the Jupyter Notebook or Python scripts to train and generate captions for images.</li></ol>


