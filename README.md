# X ray classification, performances comparaison of : Con2D, lightConv2D, transfert learning
Comparison of differents architectures of CNN for X-ray classification using Keras & Tensorflow.

## Intro
Deep learning techniques have revolutionized the field of Machine Learning (ML). In particular convolutional neural networks (CNN) for image processing. However, the downsides of CNNs are that they require an enormous amount of data, training time, and storage. The aim of this study was to compare the performance and resources required to train, export and use different convolutional neural network (CNN) solutions (blank network, transfer learning, LightLayers). For this a dataset of medical images was used to compare different indicators. As a result, it would seem possible to achieve with LightLayers results at least comparable to a transfer learning model, with a size representing only 0.5% of the latter.

## Configuration
Environment : Kaggle notebook with GPU 

Libraries used : TensorFlow, Keras, Pandas, Numpy, Matplotlib

## Previous work / inspiration source
* Kermany, D. S., Goldbaum, M., Cai, W., Valentim, C. C., Liang, H., Baxter, S. L., ... & Zhang, K. (2018). Identifying medical diagnoses and treatable diseases by image-based deep learning. Cell, 172(5), 1122-1131 : https://www.cell.com/cell/fulltext/S0092-8674(18)30154-5#secsectitle0015
* Jha, D., Yazidi, A., Riegler, M. A., Johansen, D., Johansen, H. D., & Halvorsen, P. (2021). LightLayers: Parameter Efficient Dense and Convolutional Layers for Image Classification. arXiv preprint arXiv:2101.02268. (https://arxiv.org/pdf/2101.02268v1.pdf)

## Data
Chest X-Ray Images (Pneumonia). Available on :
* Kaggle (https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)
* Mendeley Daya (https://data.mendeley.com/datasets/rscbjbr9sj/3) 

## Notebook
Were tested :
* Lightlayers (k = 1-5)
* CNN
* Transfert learning (Inception V3)

Notebook => https://github.com/xavierbarbier/x_ray_lightlayers/blob/main/x-ray-lightlayers.ipynb

## Slides (in french)
Slides => https://github.com/xavierbarbier/x_ray_lightlayers/blob/main/x-ray-lightlayers_presentation.pdf

## Research paper (in french)
Document => https://github.com/xavierbarbier/x_ray_lightlayers/blob/main/x-ray-lightlayers_rapport.pdf

