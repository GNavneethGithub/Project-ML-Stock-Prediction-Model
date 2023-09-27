# Enhanced Machine Learning Stock Prediction Model

## Introduction
This project is an endeavor to delve deeper into the domain of stock price prediction using machine learning techniques, inspired by the MachineLearningStocks project by robertmartin8 on GitHub. The primary objective is to reproduce and enhance the original model to improve its accuracy and efficiency in predicting stock price movements.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: Pandas, Scikit-learn

## Dataset
The dataset comprises historical stock prices and fundamental metrics. It has been cleaned and prepared using Pandas to ensure a reliable basis for machine learning application.

## Methodology
Utilizing a Scikit-learn classifier, the project explores the relationship between stock fundamentals (e.g., PE ratio, debt/equity ratio, float, etc.) and the subsequent annual price change compared to a selected index. A simplistic backtest is conducted post-model application to evaluate its performance, followed by generating predictions on current data.

## Extending the Project

The project is designed to be a springboard for further exploration and improvement. Some avenues for extension include:

- Exploring alternative data sources or acquiring more extensive datasets.
- Experimenting with different machine learning models and tuning hyperparameters.
- Enhancing the backtesting framework to provide more accurate performance assessments.
- Incorporating additional features or creating composite indicators to improve prediction accuracy.

## Results
The model has shown promising results with an approximate 20% return on backtest and a 10-15% return on live trading scenarios. While these results are encouraging, this project serves as a stepping stone towards building a more robust and profitable trading system.

## Visualizations
Various visualizations have been integrated to better interpret the model's performance and the underlying trends within the data.


## Acknowledgments
This project has been significantly inspired by the work of [robertmartin8](https://github.com/robertmartin8) and his MachineLearningStocks project. The foundational ideas and initial codebase provided by robertmartin8 have been instrumental in guiding this project. A hearty acknowledgment to robertmartin8 for his valuable contribution to the community, which has served as a learning platform for many, including myself.

## Disclaimer
This project is intended for educational purposes only. The backtested performance may not accurately represent the model's future performance, and any trading decisions based on this model are made at one's own risk.
