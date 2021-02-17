# Lung-Disease-Classifiers
Multiple Machine Learning Classifiers to identify various types of lung disease
# Lung-Disease-Classifiers
Multiple Machine Learning Classifiers to identify various types of lung disease: pneumonia, COVID-19, and lung cancer(coming soon).
Used VGG-16 and ResNet50 to build pneumonia and COVID classifiers. Pneumonia classification with 92%, 98%, and 95% accuracy on test batches. COVID-19 validation accuracy was above 96% at end.

Example image of pneumonia x-ray:

![person2_bacteria_3](https://user-images.githubusercontent.com/63683831/107109286-ef092580-67f3-11eb-983e-997d66f6ddc2.jpeg)


Example image of COVID-19 CT Scan:

![Covid (1)](https://user-images.githubusercontent.com/63683831/107109297-1102a800-67f4-11eb-8c3c-d45c88807762.png)

Architecture of pneumonia model: VGG-16(VGG-16 architecture pretrained on ImageNet with modified top).

VGG Architecture:

![vgg](https://miro.medium.com/max/850/1*_Lg1i7wv1pLpzp2F4MLrvw.png)

Architecture of COVID-19 Model(Bagging ensemble of VGG-16 and ResNet50 models pretrained on ImageNet below):

![Screenshot (172)](https://user-images.githubusercontent.com/63683831/107109321-5626da00-67f4-11eb-937b-61aaac181f73.png)
COVID-19 Final Graph:

![download](https://user-images.githubusercontent.com/63683831/107132427-ea944980-6893-11eb-8ee2-871e7f9db65c.png)


ResNet Architecture:

![rowan](https://www.researchgate.net/publication/331364877/figure/fig3/AS:741856270901252@1553883726825/Left-ResNet50-architecture-Blocks-with-dotted-line-represents-modules-that-might-be.png)

Works Cited:

https://arxiv.org/abs/1512.03385

https://www.kaggle.com/andrewmvd/covid19-ct-scans

https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

https://arxiv.org/abs/1409.1556
