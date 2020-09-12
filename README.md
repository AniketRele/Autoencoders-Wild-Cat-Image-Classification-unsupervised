# Autoencoders Wild Cat Image Classification unsupervised and Image retrieval

I have created an Autoencoder model to classify the images of the Wild Cats. An autoencoder is a type of artificial neural network used to learn efficient data codings in an unsupervised manner. Here I have created a basic model of autoencoder without adding up any noise to classify the images using Convolutional layers.

Using NearestNeighbor algorithm I have successfully retrieved similar images based on the eucledian distances of various wild cats.

Classifying with the help of edge detection gave better results than normal classification and the results are given below :

## PART I: Using Raw Images

## 1) Lion: 

![header image](https://github.com/AniketRele/Autoencoders-Wild-Cat-Image-Classification-unsupervised-and-Image-Retrieval/blob/master/Images%20without%20edge/lion.PNG)

## 2) Wolf: 

![header image](https://github.com/AniketRele/Autoencoders-Wild-Cat-Image-Classification-unsupervised-and-Image-Retrieval/blob/master/Images%20without%20edge/wolf.PNG)

## 3) Cheetah: 

![header image](https://github.com/AniketRele/Autoencoders-Wild-Cat-Image-Classification-unsupervised-and-Image-Retrieval/blob/master/Images%20without%20edge/cheetah.PNG)

## 4) White Tiger/Tiger: 

![header image](https://github.com/AniketRele/Autoencoders-Wild-Cat-Image-Classification-unsupervised-and-Image-Retrieval/blob/master/Images%20without%20edge/white_tiger.PNG)

Here there is a limitation of this model which is, the model does not classify between cheetahs and leopards properly as they both have spots and the difference is just of their body size. 

## PART II: Using Edge detected Images:

## 1) Lion: 

![header image](https://github.com/AniketRele/Autoencoders-Wild-Cat-Image-Classification-unsupervised-and-Image-Retrieval/blob/master/Images%20with%20edge/lion%20edge.PNG)

## 2) Tiger: 

![header image](https://github.com/AniketRele/Autoencoders-Wild-Cat-Image-Classification-unsupervised-and-Image-Retrieval/blob/master/Images%20with%20edge/tiger%20edge.PNG)

## 3) Cheetah: 

![header image](https://github.com/AniketRele/Autoencoders-Wild-Cat-Image-Classification-unsupervised-and-Image-Retrieval/blob/master/Images%20with%20edge/cheetah%20edge.PNG)

## 4) Leopard: 

![header image](https://github.com/AniketRele/Autoencoders-Wild-Cat-Image-Classification-unsupervised-and-Image-Retrieval/blob/master/Images%20with%20edge/leopard%20edge.PNG)

## 4) Fox: 

![header image](https://github.com/AniketRele/Autoencoders-Wild-Cat-Image-Classification-unsupervised-and-Image-Retrieval/blob/master/Images%20with%20edge/fox%20edge.PNG)

## 4) Wolf: 

![header image](https://github.com/AniketRele/Autoencoders-Wild-Cat-Image-Classification-unsupervised-and-Image-Retrieval/blob/master/Images%20with%20edge/wolf%20edge.PNG)

## 4) Lioness: 

![header image](https://github.com/AniketRele/Autoencoders-Wild-Cat-Image-Classification-unsupervised-and-Image-Retrieval/blob/master/Images%20with%20edge/lioness%20edge.PNG)
