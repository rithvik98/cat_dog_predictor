# cat_dog_predictor
This model predicts if the given output file contains a dog image or an cat image with a 90% accuracy.

I have used CNN to train the model to recognize if the given picture is a cat and dog.

I uploaded the meta file containing the weights so the code will execute. Incase you want to train your own model with your own dataset use the code in model_training/train.py. Change the train_path variable value to the location of your dataset folder with two subfolders, dogs and cats containing the images (if you want to use the model to distinguish between any two samples of different kind for example, car and plane change the classes variable in train.py to your class names and also name the subfolders in train_path to those names. Changes also need to be made where ever neccesary).

Larger datasets give accurate results. I have used a dataset of 4000 images each to train this model. 

To execute the model, open command prompt and go to the folder containing predict.py (I am assuming that you have python and all the modules required pre-installed else install them.). execute the code by entering:
 
 > python predict.py image_location
 
 image_location is the path to the image which you want to classify.
 
 The output shows the percentages also.
 
 


