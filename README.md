YouTube Adview Prediction
This project predicts YouTube video ad views based on various features like views, likes, comments, and video category. Using machine learning regression models, it aims to understand the factors influencing ad views to aid in content and ad strategy.

Project Structure
Data Preprocessing: Cleans data, removes outliers, and encodes categorical features.
Feature Engineering: Transforms data, including converting video duration into seconds.
Model Training: Tests several models (RandomForest, SVR, Lasso), performs hyperparameter tuning, and selects the best model.
Evaluation: Evaluates models using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R2 score.
Installation
Clone the repository and install dependencies:
bash
Place train.csv in the project directory.
Usage
Run the script to train models and evaluate performance:

bash
Copy code
python train_model.py
The best model is saved as best_random_forest_model.pkl for reuse.

Results
The project outputs evaluation metrics and identifies the most accurate model based on R2 score.
