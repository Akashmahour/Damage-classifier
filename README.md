# Damage-classifier
Goal of this notebook: <br> To classify whether the image contains damaged or un-dmages cars.<br>
Approach: Deep learning <br>
Framework used: Tensorflow<br>

In this notebook, Densenet121 pre trained model is used to classify where the image contain the damaged car or not.

Data Augmentation is used to:
1. Rescale the data 
2. to bring all the image to same dimension  i.e. 150x150

For training 1840 images are used.
For Validation 460 image are used.

Training and evaluating the model with binary crossentropy loss, accuracy, precision , recall

Conclusion: Successfully build a classifier to classify the images containing into damage and undamage cars. 


