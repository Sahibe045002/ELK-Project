## Topic- Data-Driven Insights for Optimizing Pricing, Demand, and Inventory in the Automotive Industry

## Objective
The objective of this project is to analyze automotive industry data to identify trends in **selling price**, **vehicle models**, **state-wise demand**, and **car conditions**. The analysis aims to provide actionable insights for **business decision-making** in pricing, inventory management, and understanding demand across various car makes and states.



### Dataset Overview

The dataset contains **600,000 rows** and **15 columns**, providing detailed information about vehicles and their transactions. Below is a brief description of each column:

1. **Make**: The manufacturer of the vehicle (e.g., Toyota, Honda).
2. **Model**: The specific model of the vehicle.
3. **Trim**: Additional features or variations of the model.
4. **Body**: The type of vehicle body (e.g., sedan, SUV, truck).
5. **Transmission**: Type of transmission system (e.g., automatic, manual).
6. **VIN**: The unique Vehicle Identification Number for each vehicle.
7. **State**: The state where the transaction occurred.
8. **Condition**: The condition of the vehicle (e.g., excellent, good, fair).
9. **Odometer**: The distance the vehicle has traveled, measured in miles or kilometers.
10. **Color**: The exterior color of the vehicle.
11. **Interior**: The interior features or color of the vehicle.
12. **Seller**: The seller of the vehicle (e.g., dealership or private seller).
13. **MMR**: Manheim Market Report value, representing the estimated market price of the vehicle.
14. **Selling Price**: The final selling price of the vehicle.

### Key Characteristics

- The dataset captures **transactional and descriptive details** of vehicles, making it suitable for analysis of market trends, pricing patterns, and vehicle condition assessments.
- The **large number of rows (600,000)** allows for robust statistical analysis and insights across various segments, including geography, vehicle types, and seller behavior.
- The **combination of vehicle features, market valuation (MMR), and selling price** provides a comprehensive view for pricing strategy, market demand analysis, and predictive modeling.



## Graph 1: **"Selling price VS MMR"** 
**Question:**
- How does the median selling price compare with MMR (Manheim Market Report values) across various car models?

**Analysis:**
- This scatterplot shows the relationship between the median selling price and MMR.
- The data points are clustered primarily in lower MMR ranges.
- There is a wide variance in selling prices despite MMR values staying on the lower side.

**Insight:**
- Vehicles with low-to-mid MMR values still have considerable selling price deviations.
- Only one data point lies near 9M MMR, and its corresponding selling price is quite low.

---

## Graph 2: **"State wise avg selling price"**
**Question:**
- Which states show the highest and lowest average selling prices for car makes, and what patterns can be observed?

**Analysis:**
- States `mi`, `nv`, and `Other` show different price ranges.
- The "Other" category in the state section has higher prices, depicted in red, indicating values **above 127 million**.
- Manufacturers such as **Jaguar, Land Rover, and Lexus** contribute largely to these high values.

**Insight:**
- States like Michigan (mi) and Nevada (nv) exhibit significant price fluctuations.
- Focus on the **Other** category suggests key outliers.

---

## Graph 3: **"Model VS Price"**
**Question:**
- How do vehicle models vary in median selling price, and which models dominate premium pricing?

**Analysis:**
- **Rolls-Royce** and **Ferrari** command the highest median selling prices, exceeding 150,000.
- Tesla shows a moderate price range, while brands like **Bentley** and **Aston Martin** have lower medians compared to Rolls-Royce.

**Insight:**
- Luxury and premium brands dominate higher price segments, validating strong demand for high-value vehicles.
- Tesla highlights affordable premiums within the electric car segment.

---

## Graph 4: **"MMR VS Body"**
**Question:**
- How do vehicle body types correlate with MMR values, and which are the most popular categories?

**Analysis:**
- **Sedans** dominate MMR counts with nearly 50,000 occurrences, followed by **SUVs**.
- Coupes, Hatchbacks, and Minivans show much lower MMR counts in comparison.

**Insight:**
- Sedans and SUVs are the most frequent car bodies, reinforcing their widespread popularity in the market.
- Inventory strategies could prioritize Sedans and SUVs.

---

## Graph 5: **"Color VS State"**
**Question:**
- How does the distribution of vehicle colors vary across states?

**Analysis:**
- The chart shows colors like **white, gray, and silver** are dominant, accounting for over 10% each.
- Black, green, red, and blue follow closely, with slight variations across states.

**Insight:**
- Neutral colors (white, gray, silver) dominate preferences across regions.
- Target inventory based on popular car colors.

---

## Graph 6: **"Model VS Selling Price"**
**Question:**
- Which specific car models have the highest market share based on selling price contributions?

**Analysis:**
- **Ghost (14.22%)** and **California (13.49%)** are the leading models by selling price.
- Models like **F430, SLS AMG, and M6 Gran Coupe** also command a significant portion of the market.

**Insight:**
- Exclusive car models like Ghost (Rolls-Royce) and Ferrari California capture premium selling prices.
- Allocate marketing resources for these high-value vehicles.

---

## Graph 7: **"Make VS Condition"**
**Question:**
- What is the distribution of vehicle makes based on their condition?

**Analysis:**
- Brands like **Ferrari (19.05%)**, **Bentley (16.64%)**, and **Aston Martin (18.4%)** dominate vehicle conditions.
- Lower-condition vehicles are distributed under the "Other" section (12.9%).

**Insight:**
- Premium car brands have a higher share in good condition vehicles.
- Vehicle maintenance strategies should cater to Ferrari, Bentley, and Aston Martin.

---

## Graph 8: **"Distribution by Vehicle Make"**
**Question:**
- What is the overall distribution of vehicle makes?

**Analysis:**
- The "Other" category dominates at **71.7%**, meaning many car brands have negligible market share.
- Ford (10.19%) and Chevrolet (7.14%) lead significant portions of the market.

**Insight:**
- Diversify inventory to capture fragmented "Other" brands, alongside core brands like **Ford** and **Chevrolet**.

---

## Managerial Implications
1. **Price Optimization:** Focus on luxury models like **Rolls-Royce, Ferrari, and Ghost**, as they drive higher selling prices.
2. **State-Wise Strategy:** Prioritize **Nevada, Michigan**, and unstructured "Other" regions where premium cars demand attention.
3. **Inventory Management:**
   - Sedans and SUVs have the highest popularity based on MMR values.
   - Stock vehicles with **neutral colors** (white, gray, silver) as they align with market preferences.
4. **Vehicle Make & Model:** Strategize promotions for **Rolls-Royce Ghost** and Ferrari models that dominate higher revenues.
5. **Maintenance Programs:** Premium vehicles like Ferrari, Bentley, and Aston Martin represent a significant share of good-condition cars; ensure top-tier maintenance offerings.

---

**Dash board link** - http://localhost:5601/app/dashboards#/view/44e52131-c9aa-45eb-b679-72373258f071?_g=(refreshInterval:(pause:!t,value:60000),time:(from:now-15m,to:now))&_a=()

![Screenshot from 2024-12-16 09-37-07](https://github.com/user-attachments/assets/0164e674-9a8c-4eb4-aa26-24cb858f8810)
![Screenshot from 2024-12-16 09-36-02](https://github.com/user-attachments/assets/a6327958-4a23-4b8c-b65f-41db8878fe8b)
![Screenshot from 2024-12-16 09-36-33](https://github.com/user-attachments/assets/c760bf78-58b3-4acf-8cb9-119f950d4d09)
![Screenshot from 2024-12-16 09-36-52](https://github.com/user-attachments/assets/bee61f7c-68f0-4b34-a8a7-1e852e0d2e19)
![Screenshot from 2024-12-16 09-37-58](https://github.com/user-attachments/assets/ba2ece20-5c46-4d9b-8212-aae9905cf2a4)









