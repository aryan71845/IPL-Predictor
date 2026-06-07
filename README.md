# 🏏 IPL Win Probability Predictor

A Machine Learning-powered web application that predicts the winning probability of a team during an IPL match based on the current match situation.

The model analyzes live match conditions such as runs remaining, balls remaining, wickets in hand, current run rate, and required run rate to estimate each team's chances of winning.

## 🚀 Features

* Predicts win probability in real-time
* Interactive Streamlit web interface
* Supports multiple IPL teams and venues
* Machine Learning pipeline using Scikit-learn
* Probability-based predictions instead of simple win/loss output

## 📊 Dataset

The project uses historical IPL match data:

* `matches.csv`
* `deliveries.csv`

Additional supporting datasets:

* `teams.csv`
* `teamwise_home_and_away.csv`
* `most_runs_average_strikerate.csv`

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit
* Pickle

## ⚙️ Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Feature Engineering
4. Match State Generation
5. Model Training
6. Probability Prediction
7. Streamlit Deployment

### Features Used

* Batting Team
* Bowling Team
* City
* Runs Left
* Balls Left
* Wickets Remaining
* Current Run Rate (CRR)
* Required Run Rate (RRR)

## 📂 Project Structure

```text
IPL-Predictor/
│
├── app.py
├── main_code.ipynb
├── pipe.pkl
├── deliveries.csv
├── matches.csv
├── teams.csv
├── Players.xlsx
├── teamwise_home_and_away.csv
├── most_runs_average_strikerate.csv
└── README.md
```

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/aryan71845/IPL-Predictor.git
```

Move into the project directory:

```bash
cd IPL-Predictor
```

Install dependencies:

```bash
pip install pandas numpy scikit-learn streamlit
```

Run the application:

```bash
streamlit run app.py
```

## 🎯 Example Prediction

Input:

* Batting Team: CSK
* Bowling Team: MI
* Target: 180
* Score: 120/3
* Overs: 15.0

Output:

* CSK Win Probability: 68%
* MI Win Probability: 32%

## 🔮 Future Improvements

* Add player statistics
* Incorporate venue-specific performance
* Improve model accuracy using advanced algorithms
* Deploy on Streamlit Cloud or Render
* Add live match integration

## 👨‍💻 Author

Aryan

B.Tech Student | Machine Learning Enthusiast
