The model is designed to tell the user if the image passed to it has any cracks in it.
Dataset Source:
The dataset used for the project is Concrete Crack Images for Classification downloaded from Kaggle website at the link https://www.kaggle.com/datasets/arnavr10880/concrete-crack-images-for-classification
This dataset consists of 20,000 images each of surfaces with cracks and without cracks.
Image Format:
The 40,000 images are read in gray scale format and resized into 128 X 128 X1 in order to be able to pass it through a convolutional layer. Each image data is also formatted to 32-bit floating-point number.
