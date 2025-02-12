NBA Team Performance Prediction

This project uses NBA team statistics to predict team performance, focusing on the Boston Celtics. It collects historical team data, trains multiple machine learning models, and evaluates their accuracy in predicting team wins based on key performance metrics.

📌 Features

Data Collection: Fetches NBA team statistics (Offensive/Defensive Ratings, Pace, Shooting Stats, etc.) from nba_api.

Data Processing: Cleans and merges multiple datasets into a single structured file.

Machine Learning Models: Trains Linear Regression, Decision Tree, and Random Forest models.

Predictions: Uses trained models to predict Boston Celtics' win totals based on historical data.

Visualization: Compares actual vs. predicted wins with bar charts.

📂 Data Sources

The project collects data from:

nba_api for team stats (Field Goals, Efficiency, Pace, etc.)

Merged datasets stored in .csv format for analysis

⚡ Optimizations Implemented

Optimized Model Training: Improves training efficiency by reducing redundant computations.

Vectorized Predictions: Enhances model inference speed using NumPy arrays.

📊 Model Performance

The models are evaluated using Root Mean Squared Error (RMSE) to compare actual vs. predicted wins:

Model

Full Factor Set RMSE

Five Factor Set RMSE

Linear Regression

XX.XX

XX.XX

Decision Tree

XX.XX

XX.XX

Random Forest

XX.XX

XX.XX

🚀 How to Run

1️⃣ Install Dependencies

Ensure you have the required libraries installed:

pip install nba_api pandas scikit-learn matplotlib seaborn

2️⃣ Open the Jupyter Notebook

Launch Jupyter Notebook:

jupyter notebook

Then, open Introduction_to_Python_Final_Project.ipynb.

3️⃣ Run the Notebook Cells in Order

Execute each cell from top to bottom to:

Fetch NBA data

Train machine learning models

Predict Boston Celtics' wins

Visualize results

📈 Example Output

Season   Wins   Predicted_Wins_Full   Predicted_Wins_Five
2023-24   55        54.3                     53.8
2022-23   57        56.1                     55.4
...

🏀 Future Improvements

Integrate real-time NBA data for ongoing season predictions.

Experiment with neural networks for improved accuracy.

Enhance visualizations with interactive dashboards.

🤝 Contributing

Pull requests are welcome! If you'd like to contribute, please fork the repo and submit a PR.

📜 License

This project is open-source and available under the MIT License.
