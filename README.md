### Brain Tumor Classification


Dataset used: https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri

Model used: CNN

Trained on: Google Collab with Python 3.8

### Problem Statement

To build a deep neural network which can identify what kind of tumor exists in the brain. The model is supposed to classify brain tumors between: Meningloma, Glioma,  Pitutary and no Tumors

### Dataset 

 The dataset consists of 3264 images. This is divided into Traning and Testing set ,where Traning set have 826- Glioma tumor , 247- Meningloma Tumor, 327- No Tumor,827-Pitutary Tumor and Testing set have 100 - Glioma Tumor, 115- Meningloma Tumor, 105-No Tumor, 74- Pitutary Tumor.
 
### How to run
Required Modules: Tensorflow 2.0, Numpy, Keras, Matplotlib.pyplot, Sklearn and cv2

Fetch the entire dataset to your google drive, unzip all folders and store them in one folder.
Open the notebook in Google Collab.
Mount Google Drive.

Hit me up on pagariyajanvi@gmail.com, let's talk.

OR

Open the notebook in Google Collab.
Write code pip install opendatsets 
Import opendatsets as od
Then od.download(" Paste the Dataset Link Here")


### Conclusion
When trained on 25 epochs with a batch size of 20, the model gives a training accuracy of 0.98 based on Sparse_Categorical_CrossEntropy loss function and it achieves a validation accuracy of 0.91 and a loss of around 0.17 and testing accuracy is 0.95

Please help me improve the results. Hit me up at: pagariyajanvi@gmail.com
