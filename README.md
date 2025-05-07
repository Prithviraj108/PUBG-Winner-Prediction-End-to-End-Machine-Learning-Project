# PUBG-Winner-Prediction-End-to-End-Machine-Learning-Project
To predict the win percentage (winPlacePerc) of players in the popular battle royale game PUBG using machine learning models trained on in-game statistics.
Project Overview:
Dataset: Real match data from PUBG with various in-game performance metrics (e.g., kills, damage dealt, match duration, team placement, etc.).

Target Variable: winPlacePerc – a normalized indicator of the final standing of a player in a match.

Goal: Build a regression model that can predict a player's likelihood of winning based on their performance features.

🧰 Key Steps & Techniques:
✅ Exploratory Data Analysis (EDA)
Inspected missing values and data types.

Visualized target variable distribution using histograms.

Generated correlation heatmaps to identify influential features.

✅ Data Preprocessing
Dropped irrelevant identifiers (Id, groupId, matchId).

One-hot encoded the matchType categorical column.

Applied the IQR method to detect and remove outliers.

Used StandardScaler to normalize feature values.

✅ Modeling
Trained and evaluated multiple regression models:

Linear Regression

Random Forest Regressor

Gradient Boosting Regressor

XGBoost Regressor

✅ Model Evaluation
Performance assessed using:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score (Coefficient of Determination)

Among all, XGBoost and Random Forest showed the best balance between accuracy and generalization.

📈 Results & Insights:
Feature engineering (like outlier removal and one-hot encoding) significantly improved model performance.

Models trained on cleaned and scaled data outperformed baseline models.

Provided a practical approach to real-world regression problems in gaming analytics.

🔧 Tools & Technologies:
Python, Pandas, NumPy, Matplotlib, Seaborn

Scikit-learn, XGBoost

Jupyter Notebook

💡 What I Learned:
This project deepened my understanding of:

Data preprocessing for ML workflows

Evaluating and tuning regression models

Working with high-dimensional gaming data

Applying machine learning to real-world competitive environments
