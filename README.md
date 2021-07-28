# Image-Recognition (Machine Learning)

Classify characters from the Dragon Ball Series (Kid Goku, Krillin, Tienshinhan) with accuracy of 73%.

See Jupyter notebook file. The saved model 'dragon-ball-classifier-3.h5' should be used if one wants to use this for classification.

## Detail
At first the model is trained and predicts the characters with accuracy of around 62%. It is then retrained using earlystopping, increased filter and kernel sizes on hidden layers and adds dropout layers to minimise the loss function. This improves performance by around 6% to give an accuracy of 73%.

Finally, the model is tested with some screenshots I took from the anime series and correctly classifies them.
