# wildlife_multiclass
wildlife animal multiclass classification

Purpose: 
- use images of animal faces from wildlife directory and train a multiclass model using PCA vectors.
- use trained model to identify which animals new images refers to.
		 
Requirements: 
- Spark installed

Objective :
- transform image pixels to feature vectors and being reduced using PCA  
- perform steps to extract features and label and submit to a MLlib multiclass classification models.
- use different parameters and transformations on data to identify a good model.
- find a good model that identifies the animal in the image.

To run spark :
spark-shell --master local[*] --driver-memory=1500m