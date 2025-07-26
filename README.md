# Churn Prediction Using ANN 

This is a simple Artificial Neural Network (ANN) model that I built to predict **bank customer churn** using a real-world dataset. I gave the link below.


# Data

- The dataset is taken from a real bank and includes customer details.
- Target column: `Exited` → 1 means customer left, 0 means customer stayed.


# The Preprocessing 

- Cleaned the dataset (removed useless columns).
- Converted text data like gender and geography into numbers.
- Scaled all features using `StandardScaler`.
- Handled class imbalance using **class weights**.
- Built an ANN using Keras with ReLU and Sigmoid layers
- Trained the model and plotted accuracy/loss graphs.
- Checked performance using **confusion matrix** and classification report.
- The performance became quite well after giving weights to the classes.


# The Models' Design

- **Input layer:** 11 features
- **Hidden layers:**
  - Dense(16) → ReLU
  - Dense(12) → ReLU
  - Dense(8) → ReLU
- **Output layer:** Dense(1) → Sigmoid
- Loss: `binary_crossentropy`
- Optimizer: `Adam`
- Epochs: `100`
- Batch size: `64`
  

# Metrics and Graphs 

- Model gives around **80% accuracy** on test data.
- Plotted training and validation loss/accuracy.
- Displayed confusion matrix and performance metrics like precision and recall.
  

# Test it man

1. Open the `.ipynb` file in Google Colab.
2. Upload the dataset...Here is the link :
3. 
4. # 'https://www.kaggle.com/datasets/rjmanoj/credit-card-customer-churn-prediction'
5. 
6. Run all the cells step-by-step.
7. You’ll see graphs and evaluation results at the end.


# Note

- The dataset is **imbalanced**, so class weights really help.
- You can play around with different layers or optimizers to improve accuracy.


# Stuff

- Python
- Pandas, NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
  

# Me

Made by me while learning how neural networks work on real-world datasets. ✌😁
