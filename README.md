# Beer Consumption Prediction

<p>Beer Consumption Prediction is a project done as a solution for the kaggle competition "Beer Consumption - Sao Paulo" and as a academic project.</p>

## <ins>Goals</ins>

<p>This project was done for academic purposes and aims to predict the amount of beer consumed by Brazilians, from São Paulo, according to the temperature variation.</p>

## <ins>Objectives of the project</ins>

- Understand the Dataset and cleanup unnecessary features (if required).
- Use a Linear Regression model to predict the amount of beer consumed using a a single feature.
- Show technical scores: R2, RMSE, etc.

## <ins>Strategic plan of action</ins>

1. Frame the problem.
2. Get the Data.
3. Data Cleaning (Removal of unnecessary features).
4. Explore the Data.
5. Prepare the Data (Preprocessing and feature selection).
6. Train the ML Algorithm (Linear Regression).
7. Evaluate using technical scores.

## <ins>Experiment protocol</ins>

- The dataset was divided into training and testing parts in the ratio 80:20, that means 80% of the database will be used for training and 20% for testing.
- Predictions were based on beer amount and maximum temperature.
- Preprocessing was required because the dataset contains a large number of null values after the year is over.
- After removing null data, there were 365 data rows in the dataset, whereas the total amount was 366, which was considered a small loss.
- Results were evaluated using the coefficient of determination and the mean error.

## <ins>Technologies</ins>

- Python.
<p>Made on Google Colab.</p>

## <ins>How to use </ins>

- Download the "BeerConsumptionPrediction.ipynb" file on this repository and import it on google colab.
- Download the Dataset at "https://www.kaggle.com/dongeorge/beer-consumption-sao-paulo" and import it on the "sample_data" folder on google colab.
- Run it.

## <ins>Training and test sets vs prediction</ins>

![2022-08-26 16_29_27-BeerConsumptionPrediction ipynb - Colaboratory - Brave](https://user-images.githubusercontent.com/67275098/186978110-31568171-9331-47f0-bda7-3815e74f75a2.png)

## <ins>Credits</ins>

<p> The ideia to work on this project and it's structure was shared by the teacher of Artificial Intelligence at Facamp, Carlos Caetano.</p>
<p> Other team members:</p>

- Fábio Seiji Sakai Iwashima.
