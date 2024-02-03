# Multimodal-in-multilabel-classification
This is a demo project on multimodal application in multi-label classification.

## Getting Started
For a multi-modal (text description & image input) multi-classification task, a pre-trained BERT model is utilized for word embedding in textual inputs. Additionally, multiple classic computer vision models such as ResNet, ViT, DeiT, Swin-Transformer, etc., are employed. The study involves conducting multidimensional comparisons and ablation experiments within the constraints of model size to validate the effectiveness of the multi-modal approach and to assess the performance of different models on this multi-classification task.

## Introduction
we take an image with a caption as the input and make use of two pre-trained models, i.e., a pre-trained BERT model and a pre-trained Transformer model (see figure above). We use pre-trained BERT to output the word embeddings. Note we do not consider backpropagation through the BERT model in this paper. Our Transformer models take the combination of word vectors and images as the inputs and output a probability distribution regarding each class. In addition, we set a threshold probability, the input data are assigned to a defined class when its output conditional probability is higher than the predefined threshold. In contrast to models that exclusively process either images or textual data as independent inputs, our proposed model uniquely incorporates both visual and linguistic information, fostering a more comprehensive understanding of the input data.


### Prerequisites
Python 3.x version

Check required-libraries.txt in the code folder for all the packages that need to be installed.

Please open an issue if there is any problem.

**Clone the Project:**
```
git clone https://github.com/Pengwei-Yang/Multimodal-in-multilabel-classification.git
```
### Instructions

**Dataset**

* You can visit the relevant dataset on shared Google folder:

https://drive.google.com/drive/folders/19fFLlOSbM8MxRT1guYArREwyQ3L2QM5j?usp=sharing

**Code**

* Open and run the Jupyter Notebook in the code folder, and reset the path to your own.

**Paper**

* If you need in-depth instruction on theories, please step into the paper folder.

### Authors
* **Pengwei Yang** -*Main contributor*-
（https://wwww.pengweiyang.com）

* **Chongyangzi Teng** -*Minor contributor*- （https://www.researchgate.net/profile/Chongyangzi-Teng）
* **Mengshen Guo** -*Minor contributor*- （https://www.researchgate.net/profile/Mengshen-Guo-3）

