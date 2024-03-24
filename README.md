# Retail Causal Inference Project

## Introduction

This project applies causal inference techniques in the context of the retail industry to determine the effectiveness of a promotional intervention on sales. The dataset used in this analysis is adapted from Kaggle's Store Item Demand Forecasting Challenge dataset, specifically focusing on Store 1 and its promotion of Item 1.

![Example Image](https://github.com/karan2909/Causal_Inference/blob/main/Promotion.png)


## Background

Store 1's management noticed a decline in sales for Item 1 and decided to implement a one-day promotion on May 31, 2015, with the goal of attracting more customers to purchase the product. The objective is to investigate whether this promotional intervention had a significant impact on sales or if the observed fluctuations in sales were merely due to chance.

## Objective

The primary objective of this analysis is to identify if there exists a causal relationship between the promotion of Item 1 and the subsequent sales increase. By comparing the sales patterns observed during the promotion period with those in similar stores unaffected by the promotion, we aim to determine the causal effect of the intervention on sales.

## Methodology

1. **Data Preparation**: The dataset containing historical sales data for Store 1 is preprocessed to extract relevant features such as sales volume, time periods, and promotion indicators.

2. **Causal Inference Analysis**: Causal inference techniques, specifically the CausalImpact model, are applied to the preprocessed data to estimate the causal effect of the promotion on sales. This involves comparing the observed sales data during the promotion period with counterfactual sales data derived from similar stores without promotions.

3. **Evaluation**: The results of the causal inference analysis are evaluated to determine the significance and magnitude of the causal effect. Statistical metrics and visualizations are utilized to interpret the findings and draw actionable insights.

## Results

The analysis provides insights into the effectiveness of the promotional intervention on sales for Item 1 at Store 1. By comparing the observed sales trends with counterfactual scenarios, we can ascertain whether the promotion had a statistically significant impact on sales.

## Conclusion

This project demonstrates the application of causal inference techniques in the retail industry to evaluate the effectiveness of promotional interventions on sales. The findings contribute to informed decision-making by retail managers and provide valuable insights into the causal relationships between interventions and outcomes in retail settings.

## Further Research

Future research could explore additional factors influencing sales dynamics, such as external market conditions, competitor strategies, and customer behavior. Additionally, incorporating machine learning models for demand forecasting and predictive analytics could enhance the accuracy and robustness of retail performance analysis.
