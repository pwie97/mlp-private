# Lung and Colon Cancer Detection
This notebook demonstrates the process of building a machine learning model to detect lung and colon cancer using histopathological images. The dataset contains labeled images of cancerous and non-cancerous (<em>healthy</em>) tissues. 

There are five classes in this dataset: 
- Lung benign tissue (<em>healthy</em>)
- Lung adenocarcinoma
- Lung squamos cell carcinoma
- Colon adenocarcinoma
- Colong benign tissue (<em>healthy</em>)

Therefore, this dataset is a multi-class classification.

The goal is to compare different Convolutional Neural Networks (CNNs) to explore the strengths and weaknesses of various architectures and understand which ones perform best for the chosen dataset. Ultimately, the most robust classifier (CNN) will be identified and can accurately identify cancerous lung or colon tissues from the given sample images. 

For a fair comparison of the different CNNs, it is necessary to set some guidelines / rules:
- The dataset has to be properly preprocessed.
- The same training parameters are used 


  - Learning rate
  - Batch size
  - Number of epochs
- The same optimizer is used
  - Isolates the effect of the CNN architecture on performance

Those rules will ensure that the comparison is consistent, controlled and fair.

The dataset used in this notebook is sourced from Kaggle: https://www.kaggle.com/datasets/andrewmvd/lung-and-colon-cancer-histopathological-images/data.