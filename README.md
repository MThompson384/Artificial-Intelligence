# 🧠 AI & Machine Learning Applications
**Course assignments exploring machine learning models for market analysis and forecasting**

Ever wondered how AI models can predict wine quality or forecast stock market volumes? I tackled these exact challenges by utilizing cutting-edge machine learning technologies to build intelligent prediction systems for real-world applications.
Through this coursework, I developed comprehensive solutions spanning neural networks, time series forecasting, and information theory - demonstrating practical experience with the core technologies powering modern AI and machine learning.

## 🎯 The Problem That Caught My Attention

While exploring machine learning applications, I discovered that modern AI faces three critical challenges:
- **Pattern Recognition:** How do you design neural networks that learn complex relationships in data?
- **Sequential Prediction:** How do you model time-dependent patterns for financial forecasting?
- **Information Theory:** How do you quantify uncertainty and decision-making in classification problems?

I thought: *"This sounds like exactly the kind of problem analytics could solve!"*

## 🚀 What I Built by Utilizing AI Technologies

### 🍷 [Wine Quality Nerual Network](https://github.com/MThompson384/Artificial-Intelligence/blob/main/AI_Python_Functions_%26_DL_for_Regression.ipynb)
Deep learning regression model utilizing TensorFlow and Keras
- **Multi-layer architecture** with 7-node and 5-node hidden layers using ReLU activation
- **Wine quality prediction** from chemical properties using 150 training epochs
- **Model optimization** with Adam optimizer and MSE loss function
- **Validation performance** achieving convergence with systematic error reduction

### 🧮 [AI Language Processing & Time Series](https://github.com/MThompson384/Artificial-Intelligence/blob/main/AI_Language.ipynb)
Advanced AI implementations utilizing mathematical foundations and sequential modeling
- **Custom entropy functions** built from scratch using only Python's math module
- **RNN time series modeling** for NYSE trading volume prediction with 5-lag features
- **Mathematical precision** handling edge cases and information quantification
- **Performance evaluation** achieving 0.65 test MSE on financial forecasting

## 🛠️ Technical Skills I Utilized

**Deep Learning:** Utilized TensorFlow and Keras for neural network design, training, and evaluation

**Time Series Modeling:** Utilized RNN architectures for sequential pattern recognition and forecasting

**Data Preprocessing:** Utilized StandardScaler for feature normalization and lag-based feature engineering

**Model Evaluation:** Utilized MSE metrics, validation splits, and convergence analysis for performance assessment

## 📊 Key Results

- 🎯 **Multi-layer neural networks** successfully predicting wine quality from chemical features
- 📈 **RNN models** capturing temporal patterns in NYSE trading volume data
- 🔬 **Custom entropy** calculations providing precise information theory measurements

## 🚀 Quick Start

```bash
Python
# Wine Quality Model
from keras.models import Sequential
from keras.layers import Dense

model = Sequential([
    Dense(7, activation='relu', input_shape=(12,)),
    Dense(5, activation='relu'),
    Dense(1, activation='linear')
])

# RNN Time Series Model
from keras.layers import SimpleRNN, Dropout

model = Sequential([
    SimpleRNN(12, activation='relu', input_shape=(5, 3)),
    Dropout(0.1),
    Dense(1)
])
