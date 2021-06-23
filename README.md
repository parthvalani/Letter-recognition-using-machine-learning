# Letter-recognition-using-machine-learning


<!-- ABOUT THE PROJECT -->
## About The Project

Different Machine learning algorithms for the UCI-letter recognition dataset. 

Performance comparison using Feature Extrection through Autoencoder, 1-layer neural network, PCA algorithms.

### Built With

Tools and framework used in the project. Here are a few examples.
* python
* sklearn
* keras


<!-- GETTING STARTED -->
## Getting Started

Step by step guide of how project works


### Dataset
Letter recognition dataset
* 20000 numeric values and 16 attributes (letters)
* 26 classes (alphabets)


### Installation

1. Get a dataset from [here]((https://archive.ics.uci.edu/ml/datasets/Letter+Recognition)
2. Clone the repo
   ```sh
   git clone https://github.com/parthvalani/Letter-recognition-using-machine-learning.git
   ```
3. Install python packages
   ```sh
   pip install keras pandas sklearn numpy
   ```


<!-- USAGE EXAMPLES -->
## Methodology

* load the dataset using pandas
* data scaling and one-hot encoding
* split the data in training(16000) and testing(4000) set.
* Extract features from
  1. ANN.ipynb (2-layer neural network with 20% dropout)
  2. PCA.ipynb (principal component analysis with reduced 10 attributes)
  3. AutoEncoder.ipynb (Same input and output layer with only input data)
* Lastly, use this extracted features to get accruacy from various classification methods from sklearn. 
  - Support vector machine
  - K nearest neighbor
  - Logistic Regression
  - Decision Tree
  - Naive bayes
  - Random forest
  - Extreme learning machine
* Compare all this accuracy

## Conclusion
To conclude, it can be seen that features from the simple neural network would give best accuracy with all the classification method. So, It's been proved that NN would be the best choice for the feature extraction.


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact
Parth Valani - [@parth_valani](https://www.linkedin.com/in/parthvalani/) - parthnvalani@gmail.com

Project Link: [https://github.com/parthvalani/Tweet-review-analysis](https://github.com/parthvalani/Tweet-review-analysis/)

