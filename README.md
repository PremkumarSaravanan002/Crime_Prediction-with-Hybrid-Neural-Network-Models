# Crime Prediction 
**Crime Prediction in India using Hybrid Neural Network Models:**

This is a project that predicts the crime rate for a particular using three different deep learning algorithms: **Convolutional Neural Networks (CNN), Gated Recurrent Units (GRU), and Artificial Neural Networks (ANN)**. The project was developed by [Premkumar S](https://github.com/PremkumarSaravanan002).

**Dataset:**

The dataset used in this project is this [Dataset](https://github.com/Mayank0255/Crime-Prediction-Analysis-2019/tree/master/Data%20Set/State%20and%20UT%20Wise%20Crimes), which contains information about States, Union territories, year attributes. The dataset was preprocessed using Python and the Pandas library.

**Deep Learning Models:**

We developed three different machine learning models for this project:

1. **Convolutional Neural Networks (RNN)**: A type of neural network that can handle data.

2. **Gated Recurrent Units (GRU)**: A variant of RNN that uses gating mechanisms to selectively remember or forget information from previous time steps.

3. **Artificial Neural Networks (ANN)**: A class of feedforward neural networks that can learn complex patterns and relationships between inputs and outputs.
   
4. **Hybrid Model**: A hybrid model of these three DL model that combines the results generated by the above models and uses them as input features to predict the crime.

**Meta Regressor:**
Meta regressors is a high-level model that learns to combine predictions of multiple base models like ANN,CNN,GRU to make a final predictions.
Firstly, we will use the base models then the features used in these base models become meta features for the meta regressor, here we have used SVR.
These meta features is used to train a meta regressor model.
Finally, we will get a predictions by passing new data through the meta regressor which combines all the base regressor to make a final prediction.

We used Python and the TensorFlow library to implement and train these models on Google Collaboratory.

**Results:**

We evaluated the performance of our models using several metrics, including Mean Absolute Error (MAE), Mean Squared Error (MSE), R-squared Score. Our experiments showed that the Hybrid model achieved the highest performance, with an R-squared score of *0.71*.

**Usage:**

To use our code, you can clone this repository and run the ANN_CRIME.ipynb, CNN_CRIME.ipynb, GRU_CRIME.ipynb, HYBRID_MODEL.ipynb script. The script will preprocess the dataset, train the Deep learning models, and evaluate their performance. 

**Contributing:**

We welcome contributions to this project! If you find any bugs or issues, or if you have suggestions for improvements, please feel free to open an issue or submit a pull request.

**License:**

This project is not licensed. Feel free to use the code and modify it to suit your needs.
