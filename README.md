# Melanoma Cancer Detection Using CNN
Skin cancer is a type of cancer that grows in the skin tissue, which can cause damage to the surrounding tissue, disability, and even death. In Indonesia, skin cancer is the third leading for most cancer cases after cervical and breast cancer. The accuracy of diagnosis and the early proper treatment can minimize and control the harmful effects of skin cancer. Due to the similar shape of the lesion between skin cancer and benign tumor lesions, physicians consuming much more time in diagnosing these lesions. The system was developed in this study could identify skin cancer and benign tumor lesions automatically using the Convolutional Neural Network (CNN).

- Convolutional Neural Networks
CNNs are neural networks with a specific architecture that have been shown to be very powerful in areas such as image recognition and classification. CNNs have been demonstrated to identify faces, objects, and traffic signs better than humans and therefore can be found in robots and self-driving cars.

CNNs are a supervised learning method and are therefore trained using data labeled with the respective classes. Essentially, CNNs learn the relationship between the input objects and the class labels and comprise two components: the hidden layers in which the features are extracted and, at the end of the processing, the fully connected layers that are used for the actual classification task. Unlike regular neural networks, the hidden layers of a CNN have a specific architecture. In regular neural networks, each layer is formed by a set of neurons and one neuron of a layer is connected to each neuron of the preceding layer. The architecture of hidden layers in a CNN is slightly different. The neurons in a layer are not connected to all neurons of the preceding layer; rather, they are connected to only a small number of neurons. This restriction to local connections and additional pooling layers summarizing local neuron outputs into one value results in translation-invariant features. This results in a simpler training procedure and a lower model complexity.

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)


## General Information

- Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.



## Conclusions
- Conclusion 1 > 87.05% Training accuracy and 51.00% validation accuracy.
- Conclusion 2 > 48.32% Training accuracy and 46.53% validation accuracy ( On augmented data).
- Conclusion 3 > 85.57% Training accuracy and 77.28% validation accuracy ( On rectified class imbalance data)

## Technologies Used
- Tensorflow- version 2.17.0
- Keras     - version 3.4.1
- Pandas    - version 2.1.4
- Augmentor - version 0.2.12
- Numpy     - version 1.26.4
- SNS		- version 0.13.1
- Glob


## Acknowledgements

As part of UpGrad course, casestudy on "Melanoma Detection Assignment" was taken up and applied the learnings had from Course#4_DeepLearning module.


## Contact
Created by @Aswani-ReddyKV - feel free to contact!

