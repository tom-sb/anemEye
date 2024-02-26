# anemEye
## Description
This project aims to achieve automatic segmentation of the palpebral conjunctiva.

In pursuit of this objective, various methods were tested, each of them providing a broader vision of the problem.

The first part of the model, the Encoder, seeks to extract the most relevant information so that then the second part of the model, the Decoder, can reconstruct an image of equal size by removing those parts of the image that are irrelevant to form a mask of the image. palpebral conjunctiva. The figure shows the configuration of the
model in each proposed layer in both the Encoder and Decode

![implementacion](https://github.com/tom-sb/anemEye/assets/21387081/5eed72ab-8b94-4f25-b25c-ad3f0cb42806)
