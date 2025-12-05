# Electric-Load-Forecasting-of-Godishala-Village-Substation

Electric Load Forecasting Using RNN, BiLSTM & BiGRU

A deep learning–based short-term electric load forecasting project for the 33/11 kV Godishala Substation, using advanced RNN architectures and statistical time-series analysis.

# 🚀 Overview

This project compares three sequence models:

* Vanilla RNN

* Bidirectional LSTM (BiLSTM)

* Bidirectional GRU (BiGRU)

Time-series tests such as ADF, ACF, and PACF were used to understand stationarity and autocorrelation before modeling.

# 📊 Key Results
ADF Test

ADF Statistic: −4.55

p-value: 0.000158
→ Data is stationary

Model Performance (R² Score)
Model	Train	Val	Test
Vanilla RNN	0.9316	0.84	0.9084
BiLSTM	0.9157	0.8825	0.9139
BiGRU	0.9188	0.8800	0.9133

BiLSTM and BiGRU performed best, with BiGRU offering the fastest training.


# 🔮 Future Scope

Integrate pyCity for synthetic load generation

Build a digital twin of Gandhinagar

Multi-feeder and district-level forecasting

Scenario-based forecasting (EV adoption, climate effects)

