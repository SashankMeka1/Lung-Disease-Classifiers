# Lung-Disease-Classifiers
Multiple Machine Learning Classifiers to identify various types of lung disease
# Lung-Disease-Classifiers
Multiple Machine Learning Classifiers to identify various types of lung disease: pneumonia, COVID-19.
Used VGG-16 and ResNet50 to build pneumonia and COVID classifiers. 
Pneumonia classification with 92%, 98%, and 95% accuracy on test batches. 
COVID-19 validation accuracy was above 96% at end. 
The same ensemble that was used on COVID-19 was used on lung cancer to classify adenocarcinoma(aca), sqaumous cell carcinoma(scc), and healthy lung tissue. A 96% accuracy was reached towards the end of training. 

Example image of pneumonia x-ray:

![person2_bacteria_3](https://user-images.githubusercontent.com/63683831/107109286-ef092580-67f3-11eb-983e-997d66f6ddc2.jpeg)


Example image of COVID-19 CT Scan:

![Covid (1)](https://user-images.githubusercontent.com/63683831/107109297-1102a800-67f4-11eb-8c3c-d45c88807762.png)

Example image of Adenocarcinoma(aca):

![lungaca27](https://user-images.githubusercontent.com/63683831/108273115-fd2a4080-7127-11eb-859e-b6c1e18f5547.jpeg)

Example image of Sqaumous Cell Carcinoma(scc):

![lungscc25](https://user-images.githubusercontent.com/63683831/108273204-1cc16900-7128-11eb-826b-086ead2b7bc3.jpeg)

Example image of healthy lung tissue:

![lungn17](https://user-images.githubusercontent.com/63683831/108273320-3d89be80-7128-11eb-8e32-d507838117d4.jpeg)


Architecture of pneumonia model: VGG-16(VGG-16 architecture pretrained on ImageNet with modified top).

VGG Architecture:

![vgg](https://miro.medium.com/max/850/1*_Lg1i7wv1pLpzp2F4MLrvw.png)

Architecture of COVID-19 Model(Ensemble of VGG-16 and ResNet50 models pretrained on ImageNet below):

![Screenshot (172)](https://user-images.githubusercontent.com/63683831/107109321-5626da00-67f4-11eb-937b-61aaac181f73.png)

Below is the graph of the final training epoch for the COVID-19 classifier:

![download](https://user-images.githubusercontent.com/63683831/107132427-ea944980-6893-11eb-8ee2-871e7f9db65c.png)


ResNet Architecture:

![rowan](https://www.researchgate.net/publication/331364877/figure/fig3/AS:741856270901252@1553883726825/Left-ResNet50-architecture-Blocks-with-dotted-line-represents-modules-that-might-be.png)

Works Cited:

https://arxiv.org/abs/1512.03385

https://www.kaggle.com/andrewmvd/covid19-ct-scans

https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

https://arxiv.org/abs/1409.1556
