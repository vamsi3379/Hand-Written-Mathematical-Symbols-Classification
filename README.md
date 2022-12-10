# Final Project

This is a **group assignment**.

## Code Implementation & Technical Report

The final deliverables include a 4-page IEEE-format report, code implementation and a detailed GitHub readme file.

The final project is due Tuesday, December 6 @ 11:59 PM. Find the complete [rubric](https://ufl.instructure.com/courses/455013/assignments/5244219) in the Canvas assignment.

## Training Data

The training data set is the same for every team in this course.

You can download the training data from the Canvas page:

* ["data_train.npy"](https://ufl.instructure.com/files/72247539/download?download_frd=1)
* ["t_train.npy"](https://ufl.instructure.com/files/72245951/download?download_frd=1)

# READ-ME

Table of Contents
1. About The Project
- Built With
2. Getting Started
- Dependencies
- Installation
3. Usage
4. Roadmap
5. Contributing
6. License
7. Authors
8. Acknowledgements

# About the Project

The project's objective is to build a machine-learning model that can correctly recognize a collection of mathematical symbols.We are implementing our project approach using a large data set with various symbols to be categorized by the code. The dataset is created by the team and includes 10 symbol patterns to match and classify. Each team member contributed to about 10 images of varied forms of each symbol, I.e., 100 symbols by single team member. We have used about 400 images to be classified by the algorithm. Each image in the data set can be characterized into any one of the symbols given below. Each symbol has three characteristics parameters. These parameters are Math Symbol, Label and Integer Encoding. Math symbol is the symbol pattern that needs to be matched by the algorithm with the data to classify. Label is the character equivalent of each symbol and Integer Encoding is an integer digit assigned of each symbol and the values range from 0 to 9. 

<img width="503" alt="Screen Shot 2022-12-08 at 10 56 05 PM" src="https://user-images.githubusercontent.com/48911001/206620748-cd306c35-233e-48f3-9bd4-01371a3ecf83.png">

In this project, we have used Resnet50 to classify different handwritten symbols and achieved a 90.55% over 9032 test samples. Performance of the classification can be shown using the confusion matrix between the predicted and the true values over the test can be seen in the below figure

<img width="726" alt="Screen Shot 2022-12-08 at 11 00 35 PM" src="https://user-images.githubusercontent.com/48911001/206621225-956b8041-ad02-449c-848e-f39bfc19d61b.png">

Here are some of the main citations which we have used to complete this project:

[1] R. I. Sultan, M. N. Hasan and M. Kasedullah, "Recognition of Basic Handwritten Math Symbols Using Convolutional Neural Network with Data Augmentation," 2021 5th International Conference on Electrical Engineering and Information Communication Technology (ICEEICT), 2021, pp. 1-6, doi: 10.1109/ICEEICT53905.2021.9667794. 

[2] Sakshi, Gautam, S., Sharma, C., Kukreja, V. (2021). Handwritten Mathematical Symbols Classification Using WEKA. In: Choudhary, A., Agrawal, A.P (Academic Personnel)., Logeswaran, R., Unhelkar, B. (eds) Applications of Artificial Intelligence and Machine Learning. Lecture Notes in Electrical Engineering, vol 778. Springer, Singapore. 

[3] Luo ZX, Shi Y, Soong FK (2008) Symbol graph based discriminative training and rescoring for improved math symbol recognition. In: 2008 IEEE international conference on acoustics, speech and signal processing, ICASSP 2008. IEEE, pp 1953–1956. 

[4] Kasthuri M, Shanthi V (2014) Noise reduction and pre-processing techniques in handwritten character recognition using neural networks. Technia 6(2):940

# Getting Started

## Required Dependencies

+ Tensorflow
    + python3 -m pip install tensorflow

+ OpenCV
   + pip install opencv-python

## Installation

1. Clone the Repo
    - git clone https://github.com/UF-EEL5840-F22/final-project---code-report-quadro

2. Setup (and activate) your environment
    - conda env create -f requirements.yml


# Authors

Jagan Dwarampudi - jdwarampudi@ufl.ed

Vamsi Pachamatla  - vamsi.pachamatla@ufl.edu 

Yashas Kuchimanchi - kuchimanchi.s@ufl.edu 

Veera Nitish Mattaparthi - veeramattaparthi@ufl.edu


# Thank you

