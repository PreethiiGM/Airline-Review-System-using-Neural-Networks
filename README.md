# Airline-Review-System-using-Neural-Networks
Built and trained a neural network model using Keras to predict airline flight recommendations based on customer reviews. 
The Airline Review System is a machine learning project that predicts whether a flight is recommended or not based on customer reviews and ratings. Using an Artificial Neural Network (ANN) built with Keras and TensorFlow, this model analyzes key factors such as seat comfort, food quality, inflight service, entertainment, and overall experience to determine passenger satisfaction.

This project demonstrates how deep learning can be applied in the airline industry to enhance customer experience insights, enabling airlines to improve their services based on data-driven feedback analysis.

Project Objectives

To design a neural network that predicts flight recommendations using historical passenger reviews.

To preprocess and encode categorical data for effective model training.

To visualize training accuracy and loss to evaluate model performance.

To enable real-time user input for flight recommendation prediction.

⚙️ Technologies Used

Python

TensorFlow / Keras

Pandas

Scikit-learn

Matplotlib

📂 Dataset

The dataset airlines_reviews1.csv contains various passenger review features such as:

Type of Traveller

Verified Status

Month Flown

Seat Comfort

Food & Beverages

Ground Service

Value for Money

Recommended (target variable)

All categorical values are encoded numerically using LabelEncoder for compatibility with the ANN model.

🧩 Model Architecture

The ANN model consists of:

Input Layer: Number of neurons equal to total input features

Hidden Layers:

Dense layer with 12 neurons (ReLU activation)

Dense layer with 8 neurons (ReLU activation)

Output Layer: 1 neuron (Sigmoid activation) for binary classification

Loss Function: Binary Cross-Entropy
Optimizer: Adam
Metric: Accuracy

📈 Model Training and Evaluation

The model is trained for 20 epochs with a batch size of 10.
Performance metrics such as accuracy and loss are plotted using Matplotlib to visualize the learning curve.

🧍‍♀️ User Interaction

After training, the system allows interactive prediction:
Users can input flight-related attributes (ratings, travel type, month, etc.), and the model predicts whether the flight is recommended or not.

Example output:

The flight is recommended.


or

The flight is not recommended.

🚀 Key Takeaways

Demonstrates how ANN models can process structured review data for sentiment prediction.

Highlights the importance of data preprocessing and encoding.

Can be extended to multi-class sentiment prediction or integrated into airline review dashboards.
