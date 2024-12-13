# Blinkit-Analysis
**Problem Statement**
The objective of this analysis is to evaluate the sales performance, strengths, weaknesses, and opportunities for Blinkit, focusing on:

- **Sales Insights:** Understanding overall sales trends, top-performing categories, and outlets.
- **Customer Experience:** Assessing customer ratings to identify areas for improvement.
- **Market Strategy:** Analyzing outlet types, sizes, and locations to optimize operations and future growth.
- **Product Performance:** Identifying underperforming items and planning targeted promotions.
- **Operational Challenges:** Recognizing market threats, including growth stagnation and operational costs.

**Steps Followed :**
**1. Data Preparation and Integration:**
- Consolidated data on **sales, outlet performance, and product categories**.
- Segmented data by outlet type, size, and location for detailed insights.

**2. Exploratory Data Analysis (EDA):**
- Visualized total **sales ($1.20M), average transaction size ($141), and item distribution (8,523 items).**
- Analyzed customer ratings (average 3.92), highlighting satisfaction levels.
- <img width="224" alt="image" src="https://github.com/user-attachments/assets/649a7a7b-5a57-457a-abe5-b34a6bbc6c25" />


**3. Category Performance:**
- Ranked categories by **sales, with Fruits ($178K) and Snacks ($175K) leading.**
- Identified low-performing items such as **Seafood ($9K) and Hard Drinks ($23K).**


**4. Outlet Analysis:**
- Segmented performance by location tiers **(Tier 3: $472K, Tier 2: $393K, Tier 1: $336K)**.
- Evaluated outlet size **(Medium: $508K, Small: $249K)** and type **(Supermarket Type1: $788K).**
<img width="256" alt="image" src="https://github.com/user-attachments/assets/c939ba65-593f-4f32-8573-7896f9453f31" />


**5. Trend Analysis:**
- Examined historical **sales trends (2012–2022)** showing growth stagnation after 2018.
- Forecasted potential future performance based on historical data.
<img width="262" alt="image" src="https://github.com/user-attachments/assets/70e1e25d-8d2a-43cf-bd03-f72e9456dda1" />

**6] DAX Formulae Used :**
**1. Avg Rating** = AVERAGE(('BlinkIT Grocery Data'[Rating]))
**2. Avg Sales** = AVERAGEA('BlinkIT Grocery Data'[Sales])
**3. No of items** = COUNTROWS('BlinkIT Grocery Data')
**4. Total Sales** = SUM('BlinkIT Grocery Data'[Sales])

Now using these Measures made a Parameter Metrics :
<img width="352" alt="image" src="https://github.com/user-attachments/assets/6e471646-5bb2-4dd7-9eb2-da4cb681eb16" />


SWOT Analysis:

Strengths: Strong sales and Tier 3 dominance.
Weaknesses: Low customer ratings and small outlet performance.
Opportunities: Improve customer experience and boost low-performing products.
Threats: Market saturation and rising operational costs.

Actionable Insights:

Recommended strategies to penetrate high-performing Tier 3 markets.
Suggested loyalty programs and promotions for underperforming items.
Advised on optimizing outlet operations to reduce costs and improve sales.
