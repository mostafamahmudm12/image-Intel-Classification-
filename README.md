In this project made image classification and prediction label Using CNN and fully connected layers  :



The data used in the project was Intel Image Classification It contains 6 classes and the Classes are (buildings, forest, glacier, mountain, sea, street)



In the beginning, I created some functions used in the project to display some examples of data and to display some plots to clarify the difference between traing and validation in accuracy and loss.



In the first model, it was fromscratch and without augmentation, and it contained 4 Conv2D layers and 2 fully connected layers. The accuracy in the case of training was 88% and in the validation case was 83%.And when it was prediction label he couldn't do it well.



In the second model, it was from scratch and I used augmentation, and it had the same structure as the other model,The accuracy in the case of training was 78% and in the validation case was 88%.And when it was prediction label he couldn't do it well.



In the third model, I used a more complex model in CNN, which consisted of 5 Conv2D layers and 2 fully connected layers,The accuracy in the case of training was 90% and in the validation case was 85%When it came to forecasting, I was able to do it fairly well.



In the fourth model, I used transformation learning cnn, and it was VGG16,The accuracy in the case of training was 94% and in the validation case was 88%,When it came to prediction, he was able to do it very well. 



In the fifth model, I used transformation learning cnn, which was VGG16. I used augmentation,The accuracy in the case of training was 88% and in the validation case was 85%,When it came to prediction, he was able to do it well. 



In the last mod I used Fine Tuning,The accuracy in the case of training was 99% and in the validation case was 90%,When it came to prediction, he was able to do it very well. 
