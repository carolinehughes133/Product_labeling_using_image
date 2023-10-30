# Product_labeling_using_image
Labeling product listings using product photos

# Files:
**product_labeling_using_image.ipynb**: jupyter notebook with project code

**images.csv**: dataset contains 44,447 jpg images of different articles of clothing. This will be merged to styles.csv in the project and used for predicting product labels.

**styles.csv**: dataset contains 44,447 product ids with information about the product: gender, masterCategory, subCategory, articleType, baseColour, season, year, usage, productDisplayName
we will use the images from images.csv to predict the product's articleType (i.e. Shirts, Jeans, Watches, Pants, etc.




**Motivation for using a CNN model:** <br/>
Three main reasons for using keras CNNs instead of Multilayer Perceptron (MLPs) when working with image data: <br/>

1. To use MLPs with images, we need to flatten the image. In that case spatial information (relationships between the nearby pixels) will be lost. The spatial information is required to keep certain patterns in the image. <br/>
2. CNNs can reduce the number of parameters in the network significantly. So, CNNs are parameter efficient.<br/>
3. CNNs work with both grayscale images which are often represented as a 2D array (tensor) and RGB images which are represented as a 3d array (tensor).


