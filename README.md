# Pet-Ownership-Economics-A-Comparative-Cost-Model
This Excel-based model provides a structured framework for evaluating the Total Cost of Ownership (TCO) of a domestic pet for the first year. The model serves as a template for personal budgeting and comparative cost-benefit analysis.
How it Works
​The model is divided into three logical phases to ensure data integrity:
​Initial Investment (CAPEX)
​Captures one-time costs required at the start of the lifecycle:
​Asset Purchase: Initial cost of the pet.
​Equipment: One-time purchases like collars, bowls, and leashes.
​Operational Expenditure (OPEX)
​Calculates recurring monthly costs that scale over time:
​Consumables: Food, treats, and litter.
​Monthly Aggregation: (Food + Litter + Treats) = Monthly Total.
​Annualized Lifecycle Cost
​The final calculation links the monthly volatility to a fixed annual outlook:
​Formula: Initial Total + (Monthly Total * 12) = One Year Cost.
​Visualization
​Comparative Cost Chart: A Clustered Column chart comparing the "One Year Cost" for a Dog vs. a Cat. This visualization highlights how small monthly differences (e.g., $14/month gap) compound into significant annual variances.
​Technical Implementation
​Dynamic Summation: Used range-based SUM functions to allow for easy addition of new cost line items without breaking the model.
​UI/UX: Utilized color-coded headers (Yellow for Initial, Blue for Monthly, Orange for Annual) to guide the user through the financial narrative.
​Use Case
​This model is a proof-of-concept for Budgetary Modeling. The logic can be easily pivoted to compare other recurring-cost assets, such as software subscriptions or utility plans.
