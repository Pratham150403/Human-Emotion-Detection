				Human Emotion Detection
Obtained FER-2013 dataset for emotion detection from Kaggle(dataset is too large so am uploading google drive link of the dataset). 
Set a flow path for the images using library os.
 Pre-processed the dataset using Keras.preprocessing.image and provided zoom_in,rescale,rotation_range,brightness_range,width_shift_range,horizontal_flip,height_shift_range,nearest_filling parameters.
Made a CNN-based sequential model ,inspired from VGG-16 architecture but with few layers removed based on which filters are for sensitive detection, thus obtaining a less complex model with slight loss of accuracy. 
Trained the model and saved it.
 And tested it for random index images.

https://drive.google.com/drive/folders/1bA718yUx5uASTUe6aJ5lboOm8PhyQYG3?usp=sharing