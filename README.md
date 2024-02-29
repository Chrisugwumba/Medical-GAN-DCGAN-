## Final copy of the Jupyter notebook for my master degree research Topic: Medical Image Data Augmentation Using Generative Adversarial Network (GAN). Case study of the NIH lungs dataset on kaggle

### The steps to follow in this project are as follows

Exploratory data analysis and Image preprocessing

Building and running the GAN model to generate the synthetic images

Data Preprocessing for the GAN model and involves

loading the dataset set
Creating a new column name path that will store all the the path link to each individual image
Using onehot-encoding to create the y-truth value for each image
Subsetting a single pathology to be used for the GAN model
The CNN model Process
Running a deep neural network classification model on images using the selected pathology and an approximately equal subset of healthy lungs images as the base model
Evaluate the accuracy of the base model for comparitive analysis.
Concatnate the generated synthetic image with the real images used in the training dataset, Train and evaluate the CNN model on this new dataset and measure the change in the classification models accuracy
Concatnate the generated images with the entire trsining dataset. Train and evaluate the model accuracies and matrics
