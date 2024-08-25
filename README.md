# Traffic_Sign_Recognition

### Software and Tools Requirements

1. [Github Account](https://github.com)
2. [VS Code IDE](https://code.visualstudio.com/)
3. [GitCLI](https://git-scm.com/downloads)

## Problem Description

The problem is to develop a Traffic-sign recognition system which can recognize the traffic signs put up on the road e.g. "speed limit" or "children" or "turn ahead" etc. Given the traffic signs in the image form as input, the problem is to recognize the signs using Machine learning techniques. To solve the problem following are provided:

1. A huge collection of traffic signal taken under different scene is available as input. These signs may be not clearly visible, are challenging to process as they are taken from far
2. Separate set of images are for testing the model is available

## Dataset used in the project
To implement this project, traffic sign data set is used. This data set can be downloaded from Kaggle  [here](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign).

The data set used here is from German Traffic Sign Benchmark. Data set description is as follows:

Number of images = 50,000
-   Size of the data set = around 300 MB
-   Number of classes = 43
-   The class distribution is varying
-   The train folder contains images that can be used to train
-   The path of the reading the taring images are in Train.csv file
-   Similarly, test folder has test images.

Before implementing this project ensure, the following necessary packages are installed:
-   **Keras** – CNN model building
-   **Matplotlib** and seaborn - data visualization
-   **Scikit-Learn** – Predicting and model summary
-   **PIL, CV**- Image reading and processing
-   **Pandas** – Data manipulation
