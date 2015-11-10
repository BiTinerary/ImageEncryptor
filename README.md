#Image Encrypter


This is a simple python library for encrypting images. It uses a 2-key permutation system to biject the pixels in a given image.

It currently acts on every pixel in the image. It is entirely possible (and sensible) to have the algorithm select groups of pixels to biject - this would improve computational efficiency.


For example. We can take the following image of a daisy:

![Daisy](Images/Daisy_raw.jpg)

And we can encrypt it to get:

![Encrypted_daisy](Images/encrypt.png)


This is currently a very minimalistic shell of an idea. I wrote the code during a 9 hour flight to San Francisco. Hopefully very soon I can add a slightly nicer structure and some more features!