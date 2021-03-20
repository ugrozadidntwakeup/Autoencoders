# Autoencoders
Several types of Autoencoders, application of them
## Simple Autoencoder 
The number of neurons at the input is equal to the number of neurons at the output, take BCELoss and all looking good(except for the third guy from the left, he has some troubles 😅)

![Image alt](https://github.com/ugrozadidntwakeup/Images/blob/main/image/Faces.PNG)

# Making sad people smiling
Take smiling people and sad people, so have encoding of 'smiling' and 'sad' and make a vector of 'smiling'
Then add up vector of 'smiling' to latent layer of autoencoder and give it to decoder, so let's see the result

![Image alt](https://github.com/ugrozadidntwakeup/Images/blob/main/image/smiling.PNG)

We can see that sad people took patterns(smile, facial features) of smiling and became happy(we had a 'problem' guy with a cap again 😥)

# Another type: Variational Autoencoder 
Tried to do it on MNIST and let's look a result 

![Image alt](https://github.com/ugrozadidntwakeup/Images/blob/main/image/MNIST.PNG)

Сan you guess where are the real pictures and where is the result?

# Image morphing
Take photo of one person and transform it to photo of another person using Autoencoder

