# Natural Language Processing


<p align="justify">
    The main project covers data collection from 15 different subjects from various country to imagine both 0 and 1. Subjects are given a sample image of 0 and 1 before being asked to recall the image by closing their eyes without looking at the image anymore. In the data processing and classification, the data is taken from the 10 seconds middle span out of 30 seconds per recording. Then, the data processing is divided into two parts: machine learning, and deep learning. For machine learning classification, after being band pass filtered within 10-13 Hz, pass through ICA and CSP preprocessing, the classification is done using LDA, logistic regression, SVM, and MLP (best result: MLP 60% classification rate). On the other hand, for the deep learning classification, after band pass filtered within 8-30 Hz,the topo-map images are produced and fed to the network. (99.68% classification rate).
</p>

<img src="images/BCI-Imagination.jp?raw=true">

<p align="justify">
    A paper for this experiment is available: https://link.springer.com/chapter/10.1007/978-981-13-9917-6_44
</p>


