# Neural Networks
### Predicting with Neural Networks 
Neural networks, also known as **artificial neural networks (ANNs)** or **simulated neural networks (SNNs)**, are a subset of machine learning and are at the heart of deep learning algorithms. They try to emulate the human brain by combining computer science and statistics to solve common problems in the field of AI.

Neural networks are comprised of node layers, containing an input layer, one or more hidden layers, and an output layer. Each node, or artificial neuron, connects to another and has an associated weight and threshold. If the output of any individual node is above the specified threshold value, that node is activated, sending data to the next layer of the network. 
Neural networks rely on training data to learn and improve their accuracy over time. They are powerful tools in computer science and artificial intelligence, allowing us to classify and cluster data at a high velocity.

Some of its applications are as follows:
- **Facial Recognition:** Neural networks are used to identify and verify individuals based on facial features.
- **Weather Forecasting:** They help in predicting weather patterns and forecasting.
- **Natural Language Processing (NLP):** Neural networks are used to process and understand human language, enabling applications like machine translation, sentiment analysis, and chatbots.
- **Speech Recognition:** Neural networks are used to convert spoken language into written text.

## Implementation
- Importing the required Libraries and reading the dataset
- Performing EDA on the dataset
- Visualizations
- Data Preprocessing
- Splitting the data into Train and Test data
- Standardization of the data
- Tuning of the Hyperparameters
  - Batch Size
  - Epochs
  - Learning Rate
  - Number of Layers and Neurons
- Building the Model using Neural Networks
  - Training the model with best parameters
  - Model Evaluation Train and Test Error
- Predictions and Finding the accuracy

## Packages Used
- pandas, numpy
- matplotlib.pyplot, seaborn
- warnings

- from sklearn.preprocessing import StandardScaler
- from sklearn.model_selection import train_test_split
- from sklearn.metrics import accuracy_score, confusion_matrix
- from sklearn.model_selection import GridSearchCV, KFold

- import keras, tensorflow
- from keras.models import Sequential
- from keras.layers import Dense, Dropout
- from keras_tuner.tuners import RandomSearch
- from scikeras.wrappers import KerasClassifier, KerasRegressor
- from tensorflow.keras.optimizers import Adam
