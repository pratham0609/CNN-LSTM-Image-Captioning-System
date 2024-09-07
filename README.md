Flickr8 dataset:
The Flickr8 dataset is a publicly available dataset of images collected
from the popular photo-sharing website, Flickr. It consists of 8,000
images, each with associated textual tags describing the content of
the image.
The images in the Flickr8 dataset are diverse in terms of content,
ranging from landscapes and animals to people and objects.
● Preprocessing
The preprocessing part of the code focuses on preparing the image
captions for further processing.
Reading Captions: The code reads captions from a CSV file that
contains image IDs and their corresponding descriptions. It extracts
the image IDs and captions from the caption file.
Descriptor Mapping: The code uses a custom dictionary class called
my_dictionary to create a mapping between image IDs and their
captions. For each image ID, multiple captions are stored as a list in
the dictionary. The captions are processed by adding a start token
("<start>") at the beginning and an end token ("<end>") at the end.
The purpose of this preprocessing is to organize the captions for
each image, making it easier to access and manipulate the data
during the subsequent steps of the code.


Architecture details and results are present in pdf uploaded.

Dataset link : https://drive.google.com/drive/folders/1RQ5qHm0aVFqWDG9VBiSnXlNPl5T15Wf_?usp=sharing
