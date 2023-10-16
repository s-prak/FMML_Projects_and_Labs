#Using a Siamese Neural Network to detect Alzheimer's Disease in brain scans

#Siamese Neural Networks

##Model

A Saimese Neural Network consists two identical subnetworks, and is a form of twin network. The networks are identical as they have the same configurations, parameters and weights. The features of each image is computed by passing a pair of images through each network. By passing the feature pairs through a euclidean distance function, the similarity is then computed. The network aims to produce a value of 0 if the images are different, and 1 if the images are same. 

##Loss Function

Cross entropy functions do not work due to the nature of SNN's. Hence, there are other types of loss functions used with SNN's. Two types are most often used. 

###Constrastive Loss

Two inputs are taken and the eudlidean distance between the image features is computed in contrastive loss. A low euclidean distance indicates points with similar features whereas a high eudlidean distance indicates points with dissimilar features.



FMML_Projects_and_Labs
