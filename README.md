# Food-Wastage-Anasysis-using-Excel
I have created an Excel project focused on food waste management. In this project, I analyzed various insights to understand the reasons for food wastage, developed a dashboard, and used linear regression forecasting to predict food waste quantities based on guest count and food quantity.

# Food Waste Management Project

## Project Overview
This project focuses on analyzing and predicting food waste to improve food management practices. Using a comprehensive dataset, the project explores key factors contributing to food waste, develops a dashboard for visualization, and applies linear regression to forecast waste based on guest count and food quantity.

## Key Features
- **Data Analysis:** Explored food wastage patterns across various dimensions like event type, food type, guest count, and seasonality.
- **Feature Engineering:** Created metrics such as wastage ratios and adjusted food quantities.
- **Linear Regression Modeling:** Predicted food wastage using key variables.
- **Dashboard Visualization:** Presented insights for actionable decision-making.

## Dataset
The dataset contains 1782 rows of data with the following key attributes:
- **Type of Food:** Category of the food (e.g., Meat, Vegetables).
- **Number of Guests:** Guest count per event.
- **Event Type:** Type of event (e.g., Corporate, Birthday).
- **Quantity of Food:** Food prepared in units.
- **Wastage Food Amount:** Actual food wasted in units.
- **Additional Attributes:** Storage conditions, pricing, preparation methods, and seasonality.

## Methodology
1. **Data Preparation:**
   - Loaded and cleaned the raw data.
   - Engineered new features like `Wastage Ratio` and `Adjusted Food Quantity`.

2. **Analysis:**
   - Analyzed key factors contributing to food wastage.
   - Identified patterns based on event type, geographical location, and pricing.

3. **Linear Regression:**
   - Modeled the relationship between food wastage, guest count, and food quantity.
   - Achieved a correlation coefficient (**Multiple R**) of 0.681, indicating moderate predictive strength.

4. **Forecasting:**
   - Predicted food wastage using the trained regression model.
   - Provided actionable predictions for future events.

5. **Dashboard:**
   - Visualized key insights through graphs and charts (dashboard not populated in the current file).

## Key Insights
- **Event Type & Seasonality:** Certain events and seasons lead to higher food waste.
- **Guest Count vs. Waste:** Higher guest counts tend to correlate with increased food waste.
- **Pricing:** Pricing strategies can influence wastage patterns.

## Files Included
- **food_wastage_data:** Raw data.
- **Feature Creation:** Includes engineered features.
- **Linear Regression:** Regression statistics and model output.
- **Forecast Waste Prediction:** Predicted wastage values.
- **Wastage Analysis:** Aggregated insights.
- **Dashboard:** Visualization for findings.

## Requirements
- **Software:** Microsoft Excel (or compatible tool for .xlsx files).
- **Python Libraries (optional):** pandas, numpy, matplotlib (if analyzing programmatically).

## Usage
1. Open the Excel file to explore individual sheets.
2. Review the `food_wastage_data` for raw information.
3. Check the `Feature Creation` sheet for engineered insights.
4. Use the `Linear Regression` sheet to understand model performance.
5. Navigate to `Forecast Waste Prediction` to view predicted values.
6. Refer to the `Dashboard` for a summary of insights.

## Future Scope
- Enhance prediction models with additional machine learning techniques.
- Expand the dataset for improved generalizability.
- Develop interactive dashboards for real-time monitoring.

## Author
- **Name:** Jitendra Prajapati
- **Focus Area:** Data analysis and forecasting for food waste management.

---
