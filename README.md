# Olympics Medals Prediction 🥇🏅

This project uses machine learning to predict the number of medals a country might win based on historical Olympic data.This is my first ML project!!

## 📌 Hypothesis

We can predict how many medals a country will win at the Olympics by using historical data and relevant predictors such as the number of athletes, participation frequency, and prior performance trends.


## 📁 Files
- `machine_learning.ipynb`: Jupyter Notebook with all the data analysis, modeling, and predictions.
- `teams.csv`: Contains data about countries and their Olympic performance.
- `athletes.csv`: Additional dataset with athlete-level information.

## 📊 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib
- Jupyter Notebook

**Project Steps**

1. Form a hypothesis.
2. Find and explore the data.
3. (If necessary) Reshape the data to predict your target.
4. Clean the data for ML.
5. Pick an error metric.
6. Split your data.
7. Train a model.

## 🤖 Regression Model Used

We used **Linear Regression** to predict the medal count for each country. The model was trained on features including:

- Number of athletes
- Total Olympic appearances
- Previous medal counts

The model works particularly well for countries with:
- A consistent history of Olympic participation
- Higher medal counts (e.g., USA, China, Russia)


## 📈 Accuracy Metric

We evaluated the model using **Mean Squared Error (MSE)** — a common regression performance metric that calculates the average of squared differences between actual and predicted medal counts.

## 💡 How to Run
1. Install dependencies
2. Open the Jupyter Notebook
3. Run the cells step-by-step.


## 🔍 Observations

- Countries with large, consistent Olympic teams yield more accurate predictions.
- Countries with fewer medals or irregular participation show less predictive accuracy.

