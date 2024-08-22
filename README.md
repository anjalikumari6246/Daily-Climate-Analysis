## Project Description
This project involves the analysis of daily climate data for the city of Delhi from 2013 to 2016. The primary goal is to explore the data, visualize trends, and build a machine learning model to forecast future temperatures. The project uses Python and several libraries for data processing, visualization, and machine learning.
## Data Source
The dataset used in this project is the [Daily Climate Time Series Data](https://www.kaggle.com/datasets/sumanthvrao/daily-climate-time-series-data) available on Kaggle. It contains daily temperature, humidity, wind speed, and pressure data for Delhi from 2013 to 2016.
## Project Structure
- `DailyDelhiClimateAnalysis.ipynb`: The Jupyter notebook containing the code for data analysis and model building.
- `README.md`: This file, explaining the project details.
- `DailyDelhiClimateTrain.csv`: The dataset used in the project.
## Requirements
To run this project, you will need the following Python libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install the necessary packages using the following command:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
## Usage
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/Daily-Climate-Analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Daily-Climate-Analysis
   ```
3. Open the Jupyter notebook in Google Colab or your local Jupyter environment:
   ```bash
   jupyter notebook DailyDelhiClimateAnalysis.ipynb
   ```
4. Run all cells to perform the analysis and model building.
## Exploratory Data Analysis (EDA)
During the EDA, several trends were observed:
- The mean temperature in Delhi generally increases from February to May, peaking around June.
- There is a strong negative correlation between temperature and humidity, indicating that higher temperatures often coincide with lower humidity levels.
- Seasonal patterns were observed in temperature and humidity, with significant variations between summer and winter months.
## Modeling and Results
A Random Forest Regressor was used to predict future temperatures based on past climate data. The model was evaluated using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

- **MAE:** 2.45°C
- **RMSE:** 3.14°C
- **R-squared Score:** 0.87

The model performs well in capturing the temperature trends, but there is room for improvement by tuning the hyperparameters or trying different algorithms.
## Conclusions
This project successfully analyzed and modeled daily climate data for Delhi. The Random Forest model demonstrated a good fit for the data, although future improvements could include more sophisticated feature engineering and hyperparameter optimization. The project showcases the potential of machine learning in weather forecasting and provides a solid foundation for further exploration.
## Future Work
- Incorporating additional weather variables like precipitation and cloud cover to improve model accuracy.
- Exploring different machine learning models such as XGBoost or LSTM for better predictions.
- Extending the analysis to include more recent data or data from other cities.
## References
- [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/user_guide.html)
- Dataset: [Daily Climate Time Series Data on Kaggle](https://www.kaggle.com/datasets/sumanthvrao/daily-climate-time-series-data)
