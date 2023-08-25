# AnimalClassification
Animal classification is a critical task in the field of biology, enabling us to understand the diversity of the animal kingdom and the relationships between different species. Model is trained on a dataset of 5 classes of animals and extracted features in order to classify them.


Methodology:
The first step is to gather a dataset of animal images with 5 breeds and preprocess the images to ensure that they are of the same size and have a consistent format. Next, the dataset will be split into training and testing sets with an appropriate ratio. To increase the size of the training dataset and prevent overfitting, data augmentation techniques such as rotation, zoom, and flip are applied. A pre-trained CNN model that has been trained on a large dataset such as ImageNet is loaded, and new layers is added on top of the pre-trained model for fine-tuning. The model is compiled by specifying the optimizer, loss function, and evaluation metric.

The fine-tuned model is trained on the augmented training set and evaluated on the testing set to measure its performance. The model weights and architecture is saved to a file for future use. The training history of the model is analyzed by plotting the accuracy and loss curves to ensure that the model is not overfitting. The model is then evaluated on new unseen data to see how well it can classify the animal images. Finally, the results are summarized, and conclusions are drawn on the effectiveness of the fine-tuned model for animal classification.

DATASET:
Dataset contains pictures of 5 animals, namely - Lion, Tiger, Cheetah, Fox and Wolf split into training and validation set. The images were procured individually and pre-processed by first changing the dimension and scaling it to a smaller range to reduce size of the dataset.




 
Test score is 0.8856485486030579
Test accuracy is 0.6947368383407593


