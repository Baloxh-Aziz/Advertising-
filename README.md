Advertising Sales Prediction
A machine learning project that predicts Sales based on TV and Radio advertising budgets using Linear Regression.
Overview
This notebook trains a regression model on the Advertising dataset to predict how much sales revenue can be expected given a TV and Radio advertising budget.
Project Structure
├── Advertising_dataset.ipynb   # Main notebook
├── requirements.txt            # Python dependencies
└── README.md
How It Works

Load data — reads advertising.csv into a pandas DataFrame
Clean data — drops the Newspaper column (not used)
Explore — inspects shape, types, and summary statistics
Prepare — uses TV and Radio as features, Sales as target
Train/Test Split — 70% train / 30% test (random_state=42)
Model — Linear Regression
Evaluate — MSE and R² Score
Visualize — Actual vs Predicted Sales scatter plot
Predict — takes user input (TV & Radio budget) and predicts sales

Results
The model outputs:

MSE (Mean Squared Error)
R² Score (how well the model fits)
Scatter Plot — Actual vs Predicted Sales

Getting Started
1. Clone the repo
bashgit clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
2. Install dependencies
bashpip install -r requirements.txt
3. Add the dataset
Download advertising.csv and place it in the project folder. Update the file path in the notebook:
pythondf = pd.read_csv('advertising.csv')
4. Run the notebook
bashjupyter notebook Advertising_dataset.ipynb
Dependencies

Python 3.8+
pandas
scikit-learn
matplotlib
jupyter

License
This project is for educational purposes.
