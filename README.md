# colorectal-histology

The repository contrains an classification on the tensorflow dataset with images of colorectal histologys. The data was presented here: Kather JN, Weis CA, Bianconi F, Melchers SM, Schad LR, Gaiser T, Marx A, Zollner F: Multi-class texture analysis in colorectal cancer histology (2016), Scientific Reports (in press) https://zenodo.org/record/53169#.XGZemKwzbmG


The data is classified in 8 classes, and contains 5000 images, equally distributed to all classes.
<br />
<br />
![](/colorectal_histology.png)
<br />
<br />

The applied model consists of several convolution and pooling layers. Also dropout and dense layers in the end are added. The model reaches around 85% accuracy on the validation set. The graph of the training and validation loss and accuracy stagnate after approximately 80 epochs, so it could be benificial to train only for that many epochs in order to prevent overfitting.
