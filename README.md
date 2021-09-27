# FeatureExtractor

## About model
This is the machine learning model that is based on the Feature Extraction Transfer Learning. Uisng this model is very easy.
* Download the dataset from github [link](https://github.com/UCSD-AI4H/COVID-CT) 
* Fork this repository and download this repository.
* Open the repository in the jupyter notebook and run the notebook.
* Following are the pre-requisites for running the model:
  * OpenCV
  * Numpy
  * Tensorflow and Keras
  * Sikitlearn library

## Baseline results:

#### Feature extractor based transfer learning

|  Metrics |  Performance | 
|---|---|
|  Train Accuracy: | 0.98 |
|  Val Accuracy:   | 0.81 |
|  Test Accuracy:  | 0.75 |
|   Precision:     | 0.76 |
|   Recall:        | 0.72 |
| F1 Score:        | 0.74 |
| AUC:             | 0.75 |

***

#### Fine tuning based transfer learning

|  Metrics |  Performance | 
|---|---|
|  Train Accuracy: | 0.99 |
|  Val Accuracy:   | 0.91 |
|  Test Accuracy:  | 0.88 |
|   Precision:     | 0.97 |
|   Recall:        | 0.79 |
| F1 Score:        | 0.87 |
| AUC:             | 0.88 |

