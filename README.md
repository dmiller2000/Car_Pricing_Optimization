# What Drives the Price of a Car?

## Project Overview
This data science project aims to identify and quantify the key factors that influence car prices in the market. By analyzing various car attributes and their relationship with price, we provide insights that can help buyers, sellers, and dealerships make informed decisions.

## [Link to Notebook](car_price_analysis.ipynb) 

https://colab.research.google.com/drive/1qhpHCJsbQRpK02bXLA1qovnRV7VDuwCc#scrollTo=LVncOjOoaqll

## Summary of Findings

### Key Price Drivers
Our analysis reveals that the most significant factors affecting car prices are:
1. **Vehicle Age**: Newer cars command higher prices, with depreciation following a predictable curve
2. **Brand Prestige**: Luxury brands maintain higher resale values
3. **Mileage**: Lower mileage correlates strongly with higher prices
4. **Engine Power/Size**: More powerful engines typically increase value
5. **Features/Options**: Advanced technology packages significantly boost price

### Model Performance
We tested several regression models to predict car prices:
- Random Forest Regressor achieved the highest performance with an R² of 0.89
- Feature importance analysis confirmed our top price drivers
- Cross-validation ensured model reliability across different data segments

### Market Insights
- The price-to-feature relationship is non-linear, with diminishing returns for additional features in budget segments.
- Regional variations exist in how certain features are valued.
- Seasonal patterns affect pricing, particularly for convertibles and 4WD vehicles.

## Business Recommendations

### For Car Buyers
- Focus on vehicles 2-3 years old for optimal value (significant depreciation already occurred).
- Compare feature packages carefully - some add more value than others.
- Consider less popular colors for potential discounts.

### For Car Sellers
- Highlight low mileage and service history prominently in listings.
- Focus on tech features and safety enhancements that add the most value.
- Time listings strategically based on seasonal demand patterns.

### For Dealerships
- Stock inventory with emphasis on the highest-value features.
- Adjust pricing models to account for regional preferences.
- Consider targeted marketing for vehicles with features undervalued by the market.

## Next Steps
Future work could include:
- Time series analysis of price trends
- Geographic market segmentation
- Competitive analysis by brand and model
- Integration of external economic indicators

## Tools and Technologies
- Python (pandas, scikit-learn, matplotlib, seaborn)
- Jupyter Notebook
- Machine Learning: Linear Regression, Ridge, Lasso, Random Forest, Gradient Boosting models
- Cross-validation and hyperparameter tuning
- Feature importance analysis

## Project Structure
```
car-price-analysis/
│
├── README.md                       # Project overview and summary
├── car_price_analysis.ipynb        # Main Jupyter notebook with analysis
└── data/                           # Data directory
    └── vehicles.csv                # Dataset of car listings
```

## Recommendations for Used Car Dealership:
----------------------------------------
1. Inventory Selection: Focus on acquiring vehicles with the features that most positively impact price.
2. Pricing Strategy: Use the model to set competitive yet profitable prices.
3. Marketing Focus: Highlight the high-value features in advertisements.
4. Seasonal Adjustment: Consider adjustments based on time-related patterns identified.
5. Customer Education: Inform customers about the key factors that influence resale value.

## Contact
For questions or collaboration opportunities, please contact:
David Miller ...@gmail.com.



