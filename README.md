# Vaca Muerta — Unconventional Oil Production Forecast 2026

### Time-Series Analysis and Forecasting with Python and Prophet

**Author:** Gustavo Alfredo Herrero  
**Study area:** Vaca Muerta, Neuquén Province, Argentina  
**Historical period:** 2012–2025  
**Forecast horizon:** 2026

## 1. Project Overview

This project analyzes the historical evolution of unconventional oil production from the Vaca Muerta formation in Neuquén Province, Argentina, and develops a quantitative forecast for 2026.

The study combines energy industry knowledge with time-series analysis and predictive modeling, with particular attention to the strong production growth observed in recent years.

## 2. Objectives and Scope

- Analyze monthly unconventional oil production between 2012 and 2025.
- Identify the main historical development stages and changes in production trends.
- Evaluate the performance of a univariate forecasting model based on Prophet.
- Validate predictive accuracy through historical testing and backtesting.
- Estimate monthly and annual oil production for 2026.
- Discuss forecast uncertainty and the limitations of trend-based modeling.

The study focuses exclusively on unconventional oil production associated with the Vaca Muerta formation in Neuquén Province. Tight oil and production from other formations are excluded.

## 3. Data and Methodology

The historical dataset includes monthly oil production records for 2012–2025.

Three broad development stages are considered for descriptive analysis:

- 2012–2017: Initial development.
- 2018–2022: Expansion and consolidation.
- 2023–2025: Accelerated production growth.

The forecasting methodology uses Python and Prophet, with a primary focus on modeling trend changes. Seasonality is included but plays a secondary role.

The selected modeling strategy uses 2020–2024 for training and 2025 for out-of-sample validation. Alternative model configurations were evaluated using MAPE, MAE, RMSE, and forecast bias.

## 4. Key Findings

- Production growth and structural trend changes represent the main forecasting challenge.
- The selected model uses yearly seasonality, changepoint_prior_scale = 0.03, and seasonality_prior_scale = 0.1.
- The model achieved a MAPE of approximately 3.92% for the 2024 backtesting period and 7.18% for the 2025 validation period.
- Forecast errors indicate that the model tends to underestimate production during periods of strong acceleration.
- The projected total unconventional oil production for 2026 is approximately 35.60 million cubic meters.

This forecast is a statistical baseline, not a guarantee of future production. Actual outcomes depend on investment, drilling and completion activity, infrastructure, operating conditions, and other industry factors not explicitly included in this univariate model.

## 5. Project Documentation
The following documents and supporting files are available in this repository:

### Final Research Paper
- [Download PDF](documents/Vaca_Muerta_Oil_Forecast_2026.pdf)
- [Download Word](documents/Vaca_Muerta_Oil_Forecast_2026.docx)

### Technical Appendix
- [Download PDF](documents/Vaca_Muerta_Anexo_Tecnico_2026.pdf)
- [Download Word](documents/Vaca_Muerta_Anexo_Tecnico_2026.docx)

### Historical Production Dataset
- [Excel — Monthly Oil Production 2012–2025](data/Vaca_Muerta_Serie_2012_2025.xlsx)

### Python / Jupyter Notebook
- [View Prophet Forecasting Notebook](notebooks/Vaca_Muerta_Prophet_2026.ipynb)

The technical documentation provides additional details on data preparation, model configuration, validation, forecasting results, and methodological limitations.


## 6. Professional Competencies Demonstrated

This project demonstrates the integration of professional energy-sector experience and quantitative analytical capabilities:

- Oil and gas industry and unconventional resource knowledge.
- Energy production analysis and interpretation.
- Time-series analysis and predictive modeling.
- Model validation, backtesting, and forecast diagnostics.
- Python, Pandas, Prophet, and Jupyter Notebook.
- Critical evaluation of forecasts and their operational limitations.

## 7. Author and Professional Profile

**Gustavo Alfredo Herrero**  
Energy Professional | Geologist | MSc in Energy & Environmental Policy  
Energy Analytics | Applied Data Science

[GitHub Professional Profile](https://github.com/Tavito1190)Forecasting unconventional oil production in Vaca Muerta, Neuquén, Argentina, for 2026 using Python, Prophet, time-series analysis, and model validation.
