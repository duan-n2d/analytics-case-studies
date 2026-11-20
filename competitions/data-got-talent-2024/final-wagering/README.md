# Final Round Submission for Data Got Talent 2024 by Team Pentagon
## Team Members:
- Nguyen Duy Duan
- Le Tuan Nguyen
- Phan My Kim
- Lam My Ngoc
- Tran Ngoc Bich Tran

## Project Introduction
### Company Context:
- Racing and Wagering Western Australia (RWWA) is the governing body for horse and greyhound racing in Western Australia, responsible for ensuring the vitality and sustainability of this industry in the region. As part of its mission, RWWA oversees off-course betting activities associated with racing. This is carried out through Western Australia TAB, a state-owned enterprise managing up to 300 retail betting locations and operating an online betting service branded as 'TABtouch'. WA TAB allows customers to place bets on various racing events, including horse and greyhound races, as well as a range of other sports, both domestic and international.
- TAB offers two types of betting: Fixed-odds and Pari-mutuel for both Racing and Sports categories.

## Environment Setup

To run the notebooks in this project, install the following Python libraries:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn pmdarima keras statsmodels
```

## Data

The competition data (WA TAB betting transactions and player demographics) belongs to the Data Got Talent 2024 organizers and is **not included** in this repository. Customer-level files derived from it (`CusData.csv`, `rfm_c.csv`, `rfm_2021.csv`, `rfm_2022.csv`) are not included either. The notebooks therefore cannot be re-run as-is; their saved outputs show the results.

## Project Structure

```bash
|-- data
|   |-- ForecastTotalTurnover.csv   # aggregate Q1 2023 revenue forecast
|
|-- EDA_Data.ipynb
|-- Time Series.ipynb
|-- RFM.ipynb
|-- RFMbyYear.ipynb
|-- Pentagon_Slide.pdf
|-- Pentagon_Report.pdf
```

### Description of Project Components:
- `data/ForecastTotalTurnover.csv`: Predicted revenue for Q1 2023 of the business.

- `EDA_Data.ipynb`: Explores and cleans the raw betting data (expects `TAB_Betting_Data.csv`, not included) and splits it into player demographics (`CusData.csv`) and transactions (`TransactionData.csv`).

- `Time Series.ipynb`: Converts transactions into a daily time series, builds and evaluates ARIMA, GRU and LSTM models, and forecasts revenue. Trained models (`best_arima_model.pkl`, `best_gru_model.pkl`, `best_lstm_model.pkl`) are not committed.

- `RFM.ipynb`, `RFMbyYear.ipynb`: Calculate R, F, M metrics per player across the whole dataset and separately by year to evaluate customer trends.

- `Pentagon_Slide.pdf` and `Pentagon_Report.pdf`: The team's report on predictions and business analysis. The Power BI report is linked below.

## Visualization Analysis
[Business Performance Report of WA TAB](https://app.powerbi.com/view?r=eyJrIjoiNGZiMDAwZTUtZjU3NC00YjM1LThmYjktMjBhZTg0NTljYmY0IiwidCI6IjY4NDJkZjllLTQwMmUtNDg1OC04OTNiLTY5YzIwNGUxOTgyMSIsImMiOjEwfQ%3D%3D&pageName=ReportSection&fbclid=IwAR3u9Ox69hszMHjlqyLpCYPYoOFMd0S-UV8hVDfp_lF802CL3RvBvzVc2f4_aem_ASIYly-TgWpv9NVkATJKZDRNGJ7RRZh5u-nsxj5ov1Oy6h_i9U8A5ETUQt3UtCGI3P3stsS0TotffyNo3ug5JVwM)

## Related Documents

- Data for the Final Round of Data Got Talent 2024
- Python Libraries: 
[NumPy](https://numpy.org/),
[Pandas](https://pandas.pydata.org/),
[Scikit-learn](https://scikit-learn.org/stable/),
[Matplotlib](https://matplotlib.org/),
[Seaborn](https://seaborn.pydata.org/),
[Pmdarima](https://pypi.org/project/pmdarima/),
[Keras](https://keras.io/guides/),
[Statsmodels](https://www.statsmodels.org/stable/index.html)
- [RFM Model](https://www.putler.com/rfm-analysis/)
- Deep Learning Techniques: [RNN GRU](https://www.geeksforgeeks.org/gated-recurrent-unit-networks/),
[RNN LSTM](https://www.geeksforgeeks.org/long-short-term-memory-lstm-rnn-in-tensorflow/)
- Machine Learning Techniques: [ARIMA](https://www.machinelearningplus.com/time-series/arima-model-time-series-forecasting-python/)

### Authors: `Team Pentagon` from the University of Economics and Law, VNU-HCM
