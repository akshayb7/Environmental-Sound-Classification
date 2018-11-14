## This is a Markdown file

The goal of this project is to evaluate the performance of deep-learning CNNs for the classification of urban sonic events. We will try to utilize the power of image classification of CNNs to do this by using the novel approach of turning audio files to spectrogram images and then using transfer learning to classify them. This is done because we want to utilize the recent advancements made in image classification and use transfer learning. We will be using 10-fold cross validation using the predefined folds provided in the dataset to measure the performance of the classifier.


The dataset for this project may be download from: https://urbansounddataset.weebly.com/urbansound8k.html

We can also directly download it using the command prompt as:
wget https://goo.gl/8hY5ER

and then untar it using:
tar xf 8hY5ER

Libraries needed to be installed:
1. numpy
2. pandas
3. os
4. glob
5. shutil
6. IPython
7. random
8. collections
9. matplotlib
10. librosa
11. pathlib
12. fastai 
