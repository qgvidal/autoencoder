# A NOISE DENOISING AUTOENCODER IMPLEMENTED WITH KERAS

Autoencoders are neural network models based. Their behavior and structure is really interesting. As you can see in the image below, the autoencoder structure is formed by two parts with the same shape: encoder and decoder.

![alt text](https://github.com/qgvidal/autoencoder/blob/main/images/autoencoder.jpg)


The main idea (and the interesting thing) is that, this models are able to compress and decompress information. 

Given an input in the encoder part, we can compress It through the neurons and, once the information arrives to the decoder it tries to decompress that input, creating at the output the same information as we had at the entrance of the model.  

So, knowing this, we can solve problems like image compression, encoding of information in cybersecurity applications and also, the reason for this typical exercise, remove data noise (for example in images). 

