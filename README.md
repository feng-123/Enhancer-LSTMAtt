# Enhancer-LSTMAtt： A Bi-LSTM and attention-based deep learning method for Enhancer Recognition
Enhancers are short DNA segments that play a key role in biological processes, such as accelerating transcription of target genes. Since the enhancer resides anywhere in a genome sequence, it is difficult to precisely identify enhancers. We presented a bi-directional long-short term memory (Bi-LSTM) and attention-based deep learning method (Enhancer-LSTMAtt) for enhancer recognition. Enhancer-LSTMAtt is an end-to-end deep learning model that consists mainly of deep residual neural network, Bi-LSTM and feed-forward attention. We extensively compared the Enhancer-LSTMAtt with 19 state-of-the-art methods by 5-fold cross validation, 10-fold cross validation and independent test. Enhancer-LSTMAtt achieved remarkable superiority, especially in the independent test. We realized Enhancer-LSTMAtt in a user-friendly web application that is freely available at http://www.biolscience.cn/Enhancer-LSTMAtt/. Enhancer-LSTMAtt is used not only for recognizing enhancers but also for distinguishing strong enhancer from weak enhancers. Enhancer-LSTMAtt is believed to become a promising tool for identifying enhancers.

![image](https://user-images.githubusercontent.com/52038355/177025319-fc07ad4b-6537-45fd-981a-89bf6eceaa9c.png)

## Webserver
http://www.biolscience.cn/Enhancer-LSTMAtt/

## Data
layer1: Enhancer and non enhancer.

layer2: Strong enhancer and weak enhancer.

## Operating environment
We used Python programming language along with the deep learning toolkit TensorFlow (version 2.0) to implement the Enhancer-LSTMAtt. 

We conducted 5-fold cross validation, 10-fold cross validation and independent test on the Microsoft Windows 10 operating system, which is installed on a notebook computer with 32G RAM and 6 CPUs, each with 2.60GHz. 

Each epoch costs about 25 seconds in the training process, while prediction of each sample takes no more than 2 seconds by using the trained Enhancer-LSTMAtt.

## Code interpretation
Independent testing.ipynb.ipynb: Independent test code of phase I and phase II.
