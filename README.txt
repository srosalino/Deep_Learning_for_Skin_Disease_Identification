***Overview**

In the realm of medical diagnostics, precision and efficiency are crucial, particularly in dermatology
where visual assessment is fundamental. This project harnesses the power of Deep Learning to enhance
the Accuracy of skin disease classification, a critical advancement given the subtle distinctions between
various skin conditions. Utilizing advanced convolutional neural networks, specifically pre-trained models
like DenseNet, VGG, and ResNet, this study aims to automate the analysis of dermatological images,
offering a robust tool to aid healthcare professionals.
The integration of Gradient-weighted Class Activation Mapping (Grad-CAM) provides further insights
by highlighting key areas in images that influence the model’s predictions, thus adding a layer of inter
pretability to the AI’s decision-making process. Through model training and validation, coupled with
extensive hyperparameter optimization using Optuna, this project strives to bridge the gap between clinical dermatology and artificial intelligence, potentially transforming diagnostic procedures by providing
swift, accurate, and interpretable results.


images 					-> Folder containing every image from the Fitzpatrick17k dataset


images_hair_removed 			-> Folder containing every image from the Fitzpatrick17k dataset without body hair


models 					-> Folder containing the .h5 files generated for every model tested throughout the development of the project


download_images 			-> .ipynb file used to download the Fitzpatrick17k images into the 'images' folder


fitzpatrick17k_csv	 		-> Original provided dataset


fitzpatrick17k_processed.csv 		-> Processed dataset using the 'download_images' notebook. This CSV contains the local paths to read the images in the source code notebooks


source_code_main 			-> Main notebook containing the source code for the development of the project


source_code_models_with_hair_removal 	-> Notebook serving as proof that the models using the images with removed body hair performed worse
