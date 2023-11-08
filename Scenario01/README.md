# This is for the scenario 01 

The scenario is like the following:

  A flower bouquet shop wants to enhance its customer experience by implementing an
  image classification component. The goal is to create a mobile app that allows customers to
  take pictures of flowers they encounter and receive information about the flower species,
  care instructions, and the option to order similar flowers. Develop a ML model for aforesaid
  classification with an example Dataset.

So, for this situation I've taken a dataset that consists of 5 classes namely ['daisy', 'dandelion', 'rose', 'sunflower', 'tulip'].
The entire images were of these five categories and all were initially stored in the flowers folder which consists of 5 sub-folders, each folder has one class images.
The number of folders in these 'flowers' represent one class.

So, now we have splitted the dataset into train, validation and testing sets.

In each of training, validation and testing folders there will n subfolders each representing one class.

Later, we have created the images using augmentation techniques to overcome the over-fitting issue.

Now, we have created a multi-class classification model with 3 convolutional layers, 1 flatten layer and 2 dense layers.

We have passed the data to the model and using the hyper-parameter tuning we have achieved the ""% accuracy.

Once, we are able to figure out the category of the class of the flower, then we can retrieve the suitable information from the database using the mongodb connection available with python or from the text files.

We can use the frameworks like Flask or Django for the connecting the backend (Python Programming) and frontend.

Once the data is captured/uploaded by the user, we can retrieve it or send it to the model which will be autoloaded by pickle library and perform the predictions and then return the resulting output to the frontend. 

For showing up the similiar images, once we get the category of the flower we can randomly pick some images from the folder using random library and display them to the user. In this way, we can integrate our model with the application for identification, classification, information retrieval and then showing the similiar images to the user.


## For running the above code

Install the requirements.txt libraries
Download the dataset from the url: https://www.kaggle.com/datasets/alxmamaev/flowers-recognition
Extract and store initially all the flowers images in the flowers folder.
Take this folder as base and change the necessary path's in the code and then run the scenario01.ipynb file.
