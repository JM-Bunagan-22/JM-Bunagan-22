### Hi, I'm JM 👋

**Data Analytics Professional** at MERALCO, turning raw data into decisions.

- 🔭 Currently working on dashboards, automation, and anomaly/fraud detection
- 🛠️ Tools: Python · SQL · Excel · Power BI · Dash
- 📊 Interests: geospatial analytics, time-series analysis, machine learning
- ⚡ I automate whenever I can — repeatable systems over one-off scripts

### Featured Projects
- **[Utility Consumption Anomaly Detection](https://github.com/JM-Bunagan-22/utility-anomaly-detection)** — Built a pipeline comparing rolling z-score vs. Isolation Forest on 1,400+ days of household power data. The threshold method missed everything; Isolation Forest caught ~5% of days as anomalous by looking across multiple features at once — a real illustration of why single-variable rules under-catch in fraud/anomaly detection.
- **[Delhi Climate Temperature Prediction](https://github.com/JM-Bunagan-22/delhi-climate-prediction)** — Built a regression pipeline forecasting daily mean temperature from 4 years of Delhi weather data, comparing Linear Regression, Random Forest, and Gradient Boosting on an 1,462-day train set, validated against 114 unseen days. Linear Regression won (MAE 2.1°C, R² 0.84) — cyclically-encoded seasonality captured the signal so well that tree ensembles added complexity without accuracy. Also caught and cleaned corrupted pressure readings (raw values ranged from -3 to 7,679 hPa) before modeling.
- **[London Smart Meters — Descriptive Analytics Dashboard](https://github.com/JM-Bunagan-22/london-smart-meters-analytics)** — Built an interactive Dash dashboard analyzing 3.5M+ daily readings across 5,566 London households (UK Power Networks' Low Carbon London trial), segmented by ACORN socio-demographic group and tariff type. Cross-referencing UK bank holidays against the daily series showed consumption running ~3% higher on holidays than regular weekdays — a small but consistent shift purely from behavior, no temperature change needed to explain it.
- **[London Smart Meters — Household Load Segmentation](https://github.com/JM-Bunagan-22/smart-meters-london-segmentation)** — Built a k-means segmentation pipeline clustering 5,560 London households from 3.5M+ daily consumption records (UK Power Networks' Low Carbon London trial) into 4 behavioral profiles using engineered features (avg. consumption, day-to-day variability, load factor, weekday/weekend split) rather than half-hourly load curves, keeping the pipeline lightweight enough to run entirely on daily aggregates. Cross-referencing against ACORN demographics — never used as a clustering input — showed one cluster skewing 69.5% Affluent while another split evenly 50/50 between Adversity and Comfortable with zero Affluent households, suggesting consumption behavior alone tracks socioeconomic grouping surprisingly well.

### Let's connect
[LinkedIn](https://www.linkedin.com/in/jm-bunagan/) · [Email](mailto:jmbunagan@gmail.com)
