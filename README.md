# CNN based Car Classification
This project is about car classification for stanford car dataset: https://ai.stanford.edu/~jkrause/cars/car_dataset.html.  The Cars dataset contains 16,185 images of 196 classes of cars. The data is split into 8,144 training images and 8,041 testing images, where each class has been split roughly in a 50-50 split. Classes are typically at the level of Make, Model, Year, e.g. 2012 Tesla Model S or 2012 BMW M3 coupe.

It is difficult to directly train deep learning model on this dataset because the limited number of images. Thus I decided to use transfer learning, a common approch used in deep learning to utilize the pretrained model on imagenet and fine-tune on our own dataset, i.e. car dataset.

This project can show you how to train and fine-tune a deep learning model using kera (tensorflow backend).
