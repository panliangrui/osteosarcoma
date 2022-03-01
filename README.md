# osteosarcoma
Noise-reducing attention cross-fusion transformer for histological image classification of osteosarcoma

![image](https://user-images.githubusercontent.com/46208253/156132355-26a984ec-32cc-43f4-b111-7b12b8f1aac3.png)

Fig .1 Overview and structure of the DCA-ACFL framework. The DCA-ACFL framework is shown in Fig . (a). As shown in Fig .1 (b), the framework uses a denoising convolutional automatic noise reduction machine to process the noisy image. Then, the noise-reduced image has two branches to process image patches of different sizes. After all image patches are embedded in position, CLS Token is introduced. After feature extraction through multiple residual self-attention mechanisms in two independent transformers, all information is passed to the next layer, as shown in Fig .1 (c). The attention cross fusion layer is based on the image information and location information carried by the CLS Token for feature fusion and performance improvement as shown in Fig .1 (d). Finally, the image features are further trained and classified by the residual neural network, as shown in Fig .1 (e).

****Code will be uploaded soon.****
