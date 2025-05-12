Python notebooks to embed street view images with StreetCLIP and use those embeddings to predict the geolocation of street view images. 

The training dataset is from Kaggle: https://www.kaggle.com/datasets/ayuseless/streetview-image-dataset
coordinates.csv has indexes that correspond to the kaggle Streetview_Images_Dataset folder (ie 0.png corresponds to the 0th row in coordinates.csv)

image_embeddings.npy contains the StreetCLIP image embeddings of each image in the training (Kaggle) dataset. Code to regenerate these embeddings is in generate_streetCLIP_embeddings.ipynb. The indexes of image_embedding.npy correspond with the indexes in coordinates.csv

The dataset used for testing the models is from HuggingFace: https://huggingface.co/datasets/stochastic/random_streetview_images_pano_v0.0.2

training_image_distribution.png shows the distribution of image locations from the training (Kaggle) dataset.


