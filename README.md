# GadgetGrid-Ecommerce-Analysis

# Overview
GadegtGrid is a global e-commerce company founded in 2018 that sells popular electronics from brands such as Apple, Samsung, and Lenovo through its website and mobile app. A little over a year after its founding, GadgetGrid experienced a significant surge in sales during the COVID-19 pandemic, as global demand for remote work and home technology solutions increased sharply. However, as the pandemic-driven demand subsided, the company began to see a notable decline in sales through 2021 and 2022.

In response, GadgetGrid’s marketing, operations, and product teams sought to better understand the key factors driving these changes in performance. The following analysis examines company data from 2019 through 2022 to identify trends, assess the effectiveness of marketing and product initiatives, and provide actionable insights to guide future growth strategies. The stakeholders want to focus on the following examples:

## Key Analyses
-	Overall **sales trends**
-	Month-over-month **seasonal growth rates** in sales
-	**Loyalty program** performance
-	**Apple products** – refunds rates, total number of refunds, and average order values (AOV)

# Entity Relationship Diagram (ERD)
-The relationship between the fields and how they connect with each other. 
![Image](https://github.com/user-attachments/assets/ab2afc77-25f3-456b-b332-19766ca9ba81)

## Overall Trend in Sales 2019-2022
-	Sales surged in 2020, primarily due to pandemic-related shifts in consumer behavior.
-	Beginning in 2021, sales declined as pandemic-driven purchasing slowed.

<div align="center">
      
| <big>Total Sales</big> | <big>Total Order Volume</big> | <big>AOV</big> |
|---------------------|---------------------|---------------------|
|    $28M   |     108K   |     $260  |

</div>

<p align="center">
  <img width="700" alt="Sales (3)" src="https://github.com/user-attachments/assets/a0f48562-e05e-44ca-a82e-99365f154d64" />
</p>

<div align="center">
<table>
  <tr>
    <td><img width="600" alt="Orders (3)" src="https://github.com/user-attachments/assets/f7aeadd3-76ae-4d15-9786-03e1547ca6ca" /></td>
    <td><img width="600" alt="AOV (3)" src="https://github.com/user-attachments/assets/84786c59-b08d-4f8d-b2f9-f3ea837794a2" /></td>
  </tr>
</table>
</div>

## Key Insight: Four Core Products Drive 96% of Revenue
<img width="2448" height="1026" alt="image" src="https://github.com/user-attachments/assets/f1a516ea-d491-4fcf-8bee-3e73ce667198" />
- The 27" 4K Gaming Monitor, Apple Airpods Headphones, Apple Macbook Air Laptop, and Lenovo ThinkPad Laptop together consistently made up 96% of Revenue.
- Revenue share of the two laptops reached 42% ($4.2m) in 2020, and fell to 27% ($1.4m) by 2022, because of fewer orders. AOVs tend to be high ($1.1k-$1.6k), suggesting reduced demand for high-end products.
For the Product Team, declining revenue from high-value products points to growing price sensitivity among customers, so GadgetGrids may need to shift away from premium products and target a more price-conscious segment.

## Month-over-Month Order Volume Growth Rates
-	Varied significantly over the analysis period, reflecting external market conditions and shifts in consumer behavior. 
-	Highest growth rate **46.2%** in **March 2020**
-	Lowest growth rate **-46.9%** in **October 2022**
-	**Seasonality patterns:**
      - **Positive** growth in **November** and **December**
      - **Negative** growth in **February** and **October**

<div align="center">
<img width="700" alt="MoM" src="https://github.com/user-attachments/assets/6d71ad06-bc55-4341-9a48-780a614671c2" />
</div>

## Loyalty Program
-	**Initially, members had less sales volume** over non-members, indicating limited early adoption and engagement. 
-	Beginning in **March 2021**, the program gained traction 
-	By the **end of 2022**, however, member sales again declined, signaling waning engagement and the need for renewed incentives.

<div align="center">
<img width="700" alt="Loyalty" src="https://github.com/user-attachments/assets/17cae1b1-d824-445b-85ef-bfbb75fdba07" />
</div>

## Refund Rates – Apple Products
-	Notable differences in **refund rates, average order value (AOV)**, and **number of refunds**.
-	**MacBook** had the **highest AOV** of **$1,588**, but it also exhibited the **highest refund rate** of **11.4%**. 
     -	Suggests potential issues that may be affecting customer satisfaction. 

<div align="center">
<img width="600" alt="Refunds" src="https://github.com/user-attachments/assets/992ef168-2ac5-4ffb-ae74-b5b9c7b4346d" />
</div>

## Key Takeaways
-	2020 growth surge is unsustainable post-pandemic.
-	Seasonality patterns should be anticipated and leveraged.
-	Loyalty program shows promise but needs re-engagement strategies.
-	The MacBook requires a deeper quality and satisfaction analysis.
-	Data-driven adjustments in marketing, product, and sales will be critical to long-term recovery and growth.

## Recommendations by Team

<table>
  <tr>
    <td width="33%" valign="top">
      
### Marketing Team

Goal: Reignite demand, strengthen customer loyalty, and stabilize sales throughout the year.
-	**Re-engage loyalty program members** through personalized email and in-app campaigns.
    -	Exclusive discounts, early access to new products, tier-based rewards, targeted marketing campaigns, personalized offers
-	**Target seasonal demand spikes** (November–December).
    -	Increase ad spending and promotional campaigns before these months.
    -	Offer bundled discounts or limited-time offers to boost AOV.
-	**Mitigate seasonal slumps** (February and October).
    -	Flash sales, referral bonuses, or “upgrade events”
-	**Gather customer feedback** from refund-related surveys to identify product experience issues that could inform both product and customer communication strategies.

    </td>
    <td width="33%" valign="top">
      
### Product Team

Goal: Improve customer satisfaction, reduce refund rates, and align products with evolving market needs.
-	**Investigate high refund rates** for MacBooks.
    -	Analyze return reasons (defects, performance issues, unmet expectations, etc.)
    -	Partner with customer support to identify recurring complaints.
-	**Enhance product quality checks** and pre-purchase information.
    -	Provide clearer product specs, comparison guides, or compatibility information online
-	**Use post-purchase surveys** to gauge satisfaction and identify early indicators of dissatisfaction.
-	**Introduce extended warranties or support plans** to increase buyer confidence, particularly for high-priced items like MacBooks.

    </td>
    <td width="33%" valign="top">
      
### Sales Team

Goal: Increase sales and capitalize on existing customer base.
-	**Leverage the loyalty program** as a retention and upselling tool.
    -	Offer bonus points for multi-product purchases or referrals.
-	**Use historical sales data**.
    -	Forecast demand for seasonal peaks and adjust inventory accordingly.
    -	Identify high-value customers and offer them exclusive upgrade offers.
-	**Collaborate with Marketing** to cross-sell and upsell during known high-growth months (e.g., bundle accessories with popular items).
-	**Train the sales team** to proactively communicate post-purchase support options and reduce potential refund triggers.
-	**Monitor performance metrics** (sales, order volume, AOV) regularly to track the impact of incentive programs.

    </td>
  </tr>
</table>










