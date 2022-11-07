# ImageDenoising_U-DCGAN [20221010 ~ 20221105]

## Poster Presentation : 허지혜, 한성현, 성언승

### Data 
Kaggle Covid-19 Radiography Database Covid19 Folder

### Noise
1) Gaussian Noise<br>
![image](https://user-images.githubusercontent.com/64202709/200205550-545a76ac-fd86-4248-8b9b-b941e279d6fa.png)

2) Speckle Noise<br>
![image](https://user-images.githubusercontent.com/64202709/200205561-5699789d-ccb1-487e-a4b3-f223c95a1990.png)

### Related Model
1) bm3d
2) DnCNN
3) CDAE

### Proposal Model
**U-DCGAN(U-net based Deep Convolutional Generative Adversarial Network)**
![image](https://user-images.githubusercontent.com/64202709/200205489-e3fc0deb-0f6f-4f48-9871-39ebd66d42c2.png)

### Results
![image](https://user-images.githubusercontent.com/64202709/200205617-e3f8f8eb-1901-43eb-a952-9235be7f00f7.png)
![image](https://user-images.githubusercontent.com/64202709/200205673-0a3f1307-060d-4ec0-ba58-b76873395afb.png)

- In the performance test results, the proposed U-DCGAN model showed the best performance in removing noise. This showed that image restoration was possible even for low-dose CT images obtained using low radiation doses.

- In the qualitative performance comparison, the traditional method has speckle-type noise, and the existing deep learning method was able to obtain a relatively clear reconstructed image. The proposed U-DCGAN model was able to obtain the clearest reconstructed image.

 - In the quantitative performance comparison, the traditional method showed poor performance, and among the deep learning models, the proposed U-DCGAN model showed the best overall performance on all noises than the existing deep learning models CDAE and DnCNN.
 
 
