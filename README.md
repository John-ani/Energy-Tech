**UK Electricity Demand Forecasting Using Machine Learning**

This project develops and evaluates machine learning models for short-term electricity demand forecasting on the UK National Grid. Using 15 years of half-hourly electricity demand data (2009–2024), the research compares multiple algorithms to improve forecasting accuracy and support renewable energy integration.

The models demonstrate how AI can enhance grid stability, operational efficiency, and energy transition planning.

**Project Overview**

Accurate electricity demand forecasting is essential for grid stability, energy market efficiency, and renewable integration.

This project evaluates three machine learning approaches:

- Random Forest

- Gradient Boosting

- Long Short-Term Memory (LSTM) neural networks

The research focuses on improving short-term load forecasting accuracy while quantifying the economic benefits for the UK electricity system.

**Objectives**

The key goals of this research are:

- Develop machine learning models for short-term electricity demand forecasting

- Compare performance of tree-based and deep learning models

- Identify key predictors affecting electricity demand

- Quantify economic benefits of improved forecasting

- Provide recommendations for grid operation and energy policy

**Dataset**

Source: UK National Grid

Time period: 2009 – 2024

Observations: 279,264 half-hourly records

Features include:

- Electricity demand

- Weather variables

- Renewable generation indicators

- Temporal features

- Lagged demand values

**Models Implemented**
- Random Forest

- Baseline ensemble model used for demand prediction.

- Gradient Boosting

- Improved performance using boosting techniques.

- LSTM Neural Network

- Deep learning model designed for time-series forecasting.

**Results**
Model	MAE	MAPE	R²
Random Forest	Baseline	—	—
Gradient Boosting	Improved	—	—
LSTM	318.54 MW	1.02%	0.9906

Key findings:

- LSTM achieved 17.3% improvement over Random Forest

- Lag-48 demand identified as the most influential predictor

- Renewable features contributed 22% of predictive importance

**Economic Impact**

- Improved demand forecasting could deliver approximately:

- £5.1 million annual benefits

Breakdown:

- Balancing cost reduction: £2.4M

- Reserve optimisation: £1.5M

- Curtailment reduction: £1.2M

- Projected benefits increase to £12–15M annually with 40% renewable penetration.

**Technology Stack**

Python

- TensorFlow / Keras

- Scikit-learn

- Pandas

- NumPy

- Matplotlib / Seaborn

**Key Contributions**

- UK-specific demand forecasting validation

- Renewable energy feature engineering

- Quantified economic benefits of AI forecasting

- Operational deployment framework for grid operators

**Future Work**

- Potential extensions include:

- Real-time forecasting pipelines

- Integration with smart grid data

- Reinforcement learning for grid optimisation

- Forecasting under high renewable penetration scenarios

**Author**

John<br>
MSc Computing Science – University of Northampton<br>
AI Engineer
