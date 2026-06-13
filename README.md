# E-Commerce Operational & Revenue Optimization Audit

## Project Overview
This project focuses on identifying operational bottlenecks, margin-eroding promotional policies, checkout friction, and service delivery gaps across 5,000 corporate transaction records. By utilizing Python and advanced data aggregation techniques, this audit translates raw data into a structured operational framework to maximize profit margins and protect customer lifetime value.

## Tools & Libraries Used
- **Environment:** Jupyter Notebook
- **Data Manipulation:** Python, Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn

## Deep-Dive Investigative Questions & Analytics Workflow

### Act 1: Operational Flow & Friction Track
1. **Question 1: The Fulfillment Breaking Point**
   - *Objective:* Determine the exact delivery threshold (in days) where transaction friction begins to severely degrade customer satisfaction scores.
   - *Methodology:* Analyzed the relationship between `delivery_days` and `customer_rating` using structured aggregations.

2. **Question 2: Regional Delivery Timelines**
   - *Objective:* Isolate geographic bottlenecks across logistics channels by tracking the average fulfillment time across different shipping regions.
   - *Methodology:* Grouped operational timelines by `region` to uncover geographical inefficiencies.

### Act 2: Promotional & Financial Track
3. **Question 3: Discount Elasticity Audit**
   - *Objective:* Evaluate if higher price markdowns drive an equilibrium increase in volume (`quantity`), or if they are simply eroding margins.
   - *Methodology:* Calculated correlation coefficients and built trend visualizations comparing `discount` levels against total sales and volume metrics.

4. **Question 4: Product Category Financial Leaks**
   - *Objective:* Audit product lines to identify areas where promotional strategies are decoupled from fiscal returns.
   - *Methodology:* Grouped categories side-by-side using aggregate functions to evaluate average promotional rates against gross revenue returns.

5. **Question 5: Payment Method Optimization**
   - *Objective:* Identify underlying technical or process friction across individual settlement channels.
   - *Methodology:* Analyzed checkout performance by grouping transactions by `payment_method` against total revenue and aggregate satisfaction.

6. **Question 6: Premium Customer Service Tiering**
   - *Objective:* Engineer high-value customer tracking segments to evaluate whether top-tier buyers receive a premium fulfillment experience.
   - *Methodology:* Conducted feature engineering by splitting transactions into spending tiers via row-wise custom logic, tracking comparative logistics speed (`delivery_days`).

---

## Key Data Findings & Analytical Insights

- **Logistics Bottlenecks:** A strict fulfillment breaking point occurs at **5 days**; shipping delays beyond this threshold trigger an immediate, sharp drop in customer satisfaction ratings. Furthermore, the **Southern Region** suffers from the longest delivery durations, and premium **High-Value customers** experience slightly higher delays, creating a serious retention risk.
- **Promotional Inefficiencies:** Data reveals a flat, inelastic relationship between discount rates and volume sold—higher promotional discounts **do not** drive higher purchase quantities, resulting in heavy revenue erosion. The **Clothing** category carries the highest average markdown rate but lags in total value, whereas **Electronics** maximizes sales with minimal price cuts. 
- **Checkout Channel Dynamics:** **Credit Cards** represent the platform’s high-velocity engine, driving a massive **$2,550,000 in revenue** with a perfect **3.0/3.0 satisfaction index**. Conversely, **Digital Wallets** represent a critical volume bottleneck, accounting for only **$900,000 in sales** despite boasting strong customer satisfaction (2.8/3.0).

---

## Act 3: Executive Summary Matrix

| Investigative Area | Key Data Finding / Bottleneck | Recommended Strategic Action |
| :--- | :--- | :--- |
| **Fulfillment Limits** | Delivery delays longer than 5 days trigger a sharp drop in customer ratings. High-value spending tiers are hit slightly harder by these delays, risking long-term loyalty. | Implement a strict 5-day shipping ceiling and prioritize fulfillment logistics/expedited shipping for premium, High-Value orders to protect brand trust. |
| **Discount Policies** | Higher discount rates show a neutral relationship with quantity sold (they do not drive volume) but severely erode total revenue. Clothing leaks the most margin, while Electronics performs best. | Audit and scale back flat promotional discount rates, especially in the Home and Clothing categories. Shift toward targeted loyalty rewards rather than blanket price cuts. |
| **Transactional Tiers** | Credit Cards drive the highest revenue ($2.55M) and maximum satisfaction (3/3). Digital Wallets are heavily underperforming, bringing in the lowest revenue ($900K) despite decent customer satisfaction (2.8/3). | Launch targeted marketing campaigns or checkout incentives (like cashback) to boost Digital Wallet usage, and optimize the card checkout funnel to maintain its high-volume performance. |

---

## Author
**Alishba Nadeem** *Portfolio Project: E-Commerce Revenue & Operational Optimization Audit*
