# 🚗 Parking Occupancy Forecasting Using Machine Learning

## 📌 Project Overview
Parking Occupancy Forecasting is a Machine Learning project that predicts future parking availability based on historical parking data.

The system uses a Random Forest Regression algorithm to forecast parking occupancy approximately 15 minutes ahead. It helps users understand whether a parking area is likely to have Low, Medium, or High occupancy before reaching the destination.

## 🎯 Objectives
- To analyze historical parking occupancy data.
- To predict future parking occupancy.
- To identify parking patterns based on time and day.
- To classify parking availability into Low, Medium, and High levels.
- To help users make better parking decisions.

## 🛠️ Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Machine Learning

## 🤖 Algorithm Used

**Random Forest Regression**

Random Forest Regression is used to predict future parking occupancy using multiple decision trees. It combines their predictions to produce the final occupancy estimate.

## 📂 Project Workflow

1. Import Required Libraries
2. Upload and Load Dataset
3. Explore the Dataset
4. Handle Missing Values
5. Visualize Parking Occupancy
6. Analyze Average Occupancy by Hour
7. Prepare Future Occupancy Data
8. Feature Selection and Train-Test Split
9. Train the Random Forest Regression Model
10. Predict Future Parking Occupancy
11. Evaluate Model Performance
12. Classify Parking Occupancy

## 📊 Input Features
- Current Occupancy Level
- Hour of the Day
- Day Number
- Parking Lot

## 🎯 Prediction Output
The model predicts future parking occupancy and classifies it into:

- **Low:** Below 40%
- **Medium:** 40% to below 70%
- **High:** 70% and above

## 📈 Model Evaluation
The model performance is evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

## 📉 Visualizations
The project includes:
- Parking Occupancy Distribution
- Average Parking Occupancy by Hour
- Actual vs Predicted Occupancy Graph
- Predicted Occupancy Categories

## 💻 How to Run the Project

1. Download or clone this repository.
2. Open the Jupyter Notebook in Google Colab.
3. Upload the required parking dataset when prompted.
4. Run all the notebook cells step by step.
5. View the predictions, evaluation metrics, and graphs.

## 🔮 Future Enhancements
- Develop a real-time parking availability system.
- Add live traffic and weather information.
- Provide nearby parking recommendations.
- Develop a user-friendly web or mobile application.

## 👩‍💻 Project Domain
Machine Learning

## 🏁 Conclusion
This project demonstrates how Machine Learning can be used to forecast future parking occupancy. By predicting parking availability in advance, the system can help reduce parking search time and support smarter parking management.
