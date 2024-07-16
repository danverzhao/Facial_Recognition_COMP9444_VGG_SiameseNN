# COMP9444 Group Project: Deep Face Recognition
[Click here for presentation slides](https://docs.google.com/presentation/d/1_sB9pA229NyX3D3ew4zZGrxLdDZYUGNciRHDHe4GxIk/edit?usp=sharing)

`Face_recognition_with_VGG_Face.ipynb` contains code for loading the weights of trained models into VGG face and training the feature embedding layer (last layer) of the network using Pinterest images. The model was trained using triplet images generated in the code that was inputted into the triplet loss function.

`VGG_face_results.ipynb` contains the code for computing the accuracy of the VGGFace model, and the demo visualization code.

`Siamese_allmods.ipynb` contains the code for loading all kinds of Siamese models, and finding the closest distance image in the database.

`Siamese_vgg8.ipynb` contains the code for Siamese model with 8 layers of vgg convolution. It includes the training and saving the model.

Report is in `COMP9444_Report.pdf`.
