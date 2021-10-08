# Dog Breed Classification Using CNNs
The aim of this project is to build a pipeline to process real-world, user-supplied images. Given an image of a dog, the model will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed.

# Blog
I wrote a blog in Medium explaining the different steps of the project. If you would like to read it please click on the following link: https://ariehlevyp.medium.com/dog-breed-classification-using-convolutional-neural-networks-cef89891d609

# Main files in the repository
- dog_app.ipynb: Jupyter notebook containing the code of the project
- images: folder containing the images used for the project
- saved_models: folder that serves as as placeholder to save the models we create
- haarcascades: contains an xml file of the haarcascade model
- extract_bottleneck_features.py: python script used to extract the bottleneck features

# Libraries
The libraries used were: keras, numpy, glob, random, cv2, matplotlib, tqdm, PIL, and IPython

# Summary of Analysis and Conclusions
Overall, the model was able to identify the dog breed with an 80% accuracy given an image of a dog. Further, the model performed very well in identifying what is a dog, what is a human, and what's not any of them. Which was a crucial part of the project.

# Acknowledgements
I would like to thank the Udacity team for putting up this project and for all their support during my Data Science Nanodegree course
