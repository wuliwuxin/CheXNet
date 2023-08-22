# CheXNet

## abstract

Multi-label chest X-ray (CXR) image classification aims to perform multiple disease label prediction tasks. This concept is more challenging than single-label classification problems. For instance, convolutional neural networks (CNNs) often struggle to capture the statistical dependencies between labels. Furthermore, the drawback of concatenating CNN and Transformer is the lack of direct interaction and information exchange between the two models. To address these issues, we propose a hybrid deep learning network named CheXNet. It consists of three main parts in the CNN and Transformer branches: Label Embedding and Multi-Scale Pooling module (MEMSP), Inner Branch module (IB), and Information Interaction module (IIM). Firstly, we employ label embedding to automatically capture label dependencies. Secondly, we utilize Multi-Scale Pooling (MSP) to fuse features from different scales and an IB to incorporate local detailed features. Additionally, we introduce a parallel structure that allows interaction between the CNN and the Transformer through the IIM. CNN can provide richer inputs to the Transformer through bottom-up feature extraction, whilst the Transformer can guide feature extraction in the CNN using top-down attention mechanisms. The effectiveness of the proposed method has been validated through qualitative and quantitative experiments on two large-scale multi-label CXR datasets with average AUCs of 82.56% and 76.80% for CXR11 and CXR14, respectively.

## CXR11 and CXR14

1. [CXR11](https://github.com/wuliwuxin/CTransCNN/blob/main/kaggle.com/competitions/ranzcr-clip-catheter-line-classification/data): In this study, 30,083 CXR image training data were used for multi-label sample classification due to computer limitations.

2. [CXR14](https://github.com/wuliwuxin/CTransCNN/blob/main/nihcc.app.box.com/v/ChestXray-NIHCC): Due to computational limitations, this study performed multi-label sample classification on 51759 CXR images, named CXR14, rather than the complete set of 112120 frontal images.

   **CXR11** and **CXR14** are shown in folders 'open_data/chest11' and 'open_data/chest14'.
   
## Citation

We now have a related paper that you can cite in this repository 🤗.

```
Waiting for updates
```
