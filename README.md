# shooters-shoot-machine-learning

🏀 NBA Shot Prediction Project: Shot Quality & Outcome Modeling
Welcome to our final project for [Bootcamp Name or Class], where we analyze NBA shot data to build a machine learning model that predicts shot outcomes and uncovers patterns in shooting performance across the league. Our goal is to combine statistical analysis with data storytelling to evaluate what makes a high-quality shot and how different features affect the likelihood of success.

📁 Project Structure
graphql
Copy
Edit

├── data/                     
https://www.nba.com/stats
https://www.espn.com/nba/stats
https://github.com/toddwschneider/ballr
https://toddwschneider.com/posts/ballr-interactive-nba-shot-charts-with-r-and-shiny/
https://www.basketball-reference.com/playoffs/NBA_2025.html
                              
├── notebooks/                # Jupyter/Colab notebooks for EDA and modeling

├── visuals/                  # Generated shot charts and model visualizations

├── models/                   # Saved models and evaluation scripts

🎯 Objective
Build a machine learning model to predict whether a shot attempt will be made or missed using player, location, and situational data. Evaluate performance across different modeling techniques and visualize the impact of features on outcomes.

⚙️ Tools & Technologies
Python (Pandas, NumPy, Matplotlib, Scikit-learn)

TensorFlow/Keras (for neural networks)

Jupyter / Google Colab

GitHub

Shot zone data from NBA API / ESPN

📊 Key Features Engineered
Shot distance and angle

Shot zone basic / range

Home vs. away

Defensive matchup stats (e.g., Opponent DRtg, block %, etc.)

Player-level shooting efficiency

Court location (LOC_X, LOC_Y)

Temporal context (quarter, time left)

🧠 Models Built
Model Type	Accuracy	Precision	Recall	F1 Score
Logistic Regression	59%	...	...	...
Random Forest Classifier	58%	...	...	...
Neural Network (Keras)	XX%	...	...	...

We're continuing to iterate and tune hyperparameters to push accuracy higher. Adding new features improved our performance marginally, but the challenge remains in modeling shot complexity and human factors.

📌 Highlights
🗺️ Zone-Based FG% Visuals: Interactive shot charts by court region

🔍 Feature Importance: Which variables actually affect shot success?

🧪 Model Comparison: Classic ML vs Neural Networks

🧠 Takeaways: Insights into shot quality, player tendencies, and model reliability

👥 Team
Haley Armenta 
Natalie Annas
Lisa Tafoya
Quentin Bartholomew
