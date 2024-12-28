# IPL_ScorePrediction_App
This project is a machine learning-based application that predicts the total score in an IPL match based on various match conditions and player statistics. The system leverages data preprocessing, feature encoding, and a deep learning model to make accurate predictions.

Why Deep Learning?

Humans often find it challenging to identify patterns from huge datasets, especially when considering multiple variables that affect outcomes. In the case of IPL score prediction, deep learning comes into play because it can efficiently learn from historical data and complex interactions between various factors like player performance, team dynamics, and match conditions.While traditional machine learning algorithms provide moderate accuracy, deep learning models excel in capturing intricate patterns and relationships within the data. These advanced techniques not only learn from how players and teams have performed against each other in the past but also take into account various attributes, such as the venue, batting, and bowling teams, striker, and bowler. This allows the model to deliver more precise predictions and handle the complexity of real-time IPL score prediction with higher accuracy.

Tools Used

Python: The core programming language used for building the project.

Pandas: Used for data manipulation and analysis. It handles data loading, cleaning, and preparation.

NumPy: Used for numerical operations, particularly for transforming data into arrays suitable for model input.

Matplotlib: Used for creating data visualizations, including model training history and performance graphs.

Seaborn: A visualization library used for generating advanced statistical plots.

Scikit-learn:

    LabelEncoder: For converting categorical features into numerical labels.
  
    MinMaxScaler: For scaling numerical features to a fixed range.
  
    Train-Test Split: For splitting the data into training and test sets.

TensorFlow & Keras:

    Used for building and training the deep learning model.
  
    The model architecture includes several dense layers optimized for regression.
  
    The Huber loss function is used to minimize the prediction error.

Gradio:

    Provides an easy-to-use interface for making predictions through a web-based application.

    Users can select various features (venue, teams, players) and get real-time predictions of IPL match scores.

How It Works

Input Features:

Venue

Batting Team

Bowling Team

Striker

Bowler

Data Transformation:

Categorical features are encoded using pre-trained LabelEncoders.

Features are scaled using a Min-Max Scaler fitted on the training data.

Model Prediction:

The neural network model predicts the total score based on the provided inputs.

Demo
To try the IPL Score Predictor, use the interactive interface built with Gradio.
