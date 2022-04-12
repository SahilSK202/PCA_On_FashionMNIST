# PCA_On_FashionMNIST

## Unsupervised learning on Fashion-MNIST

Fashion-MNIST is a dataset of Zalando's article images, with examples shown above. It consists of a
training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28
grayscale image, associated with a label from 10 classes: 0=T-shirt/top; 1=Trouser; 2=Pullover;
3=Dress; 4=Coat; 5=Sandal; 6=Shirt; 7=Sneaker; 8=Bag; 9=Ankle boot.
<br><br>
Choose any two out of the 10 classes and use only the test data for these two chosen classes to
complete tasks in this section. It will be better to finish reading the remaining part of this section
before choosing the two classes. Again, you may choose any two and there is no “correct” answer
about which two to choose but some choices may make your studies below more interesting than others.

## Dimentionality Reduction and Clustering 
### A) Apply PCA to all images of these two chosen classes. Visualise the top 5 eigenvectors as images and display them in the order of descending corresponding values (the one corresponding to the largest eigenvalue first).<br>

### B) Use the top 30 PCs to reconstruct 10 images, with 5 from each class (any 5 images are fine from each class). Show these 10 pairs of reconstructed and original images.<br>

### C) Visualise the two-dimensional PCA representations of all data points in a 2D plane (i.e. using the top two PCs). Use different colours/markers for the two classes for better visualisation (Hint: You need to use the class labels here for visualisation). <br>

### D) Use spectral clustering to cluster all data points as represented by the top two PCs (clustering of two-dimensional vectors, where each vector has two values, PC1 and PC2). Visualise the two clusters with different colours/markers in 2D. <br>


### E) Design a new autoencoder with five Conv2d layers and five ConvTranspose2d layers. You arefree to choose the activation functions and settings such as stride and padding. Train this new autoencoder on all images of these two chosen classes for at least 20 epochs. Plot the loss against the epoch.

