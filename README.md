# Project Report: Northwind Trading Online Store Optimization  

## 📌 Case Study  

**Company:** Northwind Trading - A profitable eCommerce platform (4+ years).  
**Core Issue:** **43% sales drop in March 2024** + surge in social media complaints.  

### 🕵️♂️ **Crisis Triggers:**  
- **Redesign Gone Wrong:**  
  - Mandatory registration at checkout (to collect customer data).  
  - Slower page loads due to unoptimized images.  
- **Team Conflicts:**  
  - *Marketing:* Prioritized data collection over user experience.  
  - *IT Team:* Acknowledged performance issues but delayed fixes.  
- **Management’s Response:**  
  > *"Better safe than sorry"* – Ordered urgent investigation despite no "obvious" issues.  
---

## DELIVERABLE 1: Qualitative & Quantitative Analysis & Recommendations

### Sales Performance Comparison: Feb 2024 (29 Days) vs. Mar 2024 (31 Days)

| **Metric**                         | **Feb 2024**       | **Mar 2024**       | **Difference**     | **% Change** |
|------------------------------------|--------------------|--------------------|--------------------|--------------|
| Total Sales Value                  | $71,626.00         | $40,620.00         | $(31,006)          | -43%         |
| Total Website Visits               | 3,136              | 2,811              | $(325)             | -10%         |
| Total Sales Transactions           | 477                | 302                | $(175)             | -37%         |
| **Average Daily Sales Value**      | $2,469.86          | $1,310.32          | $(1,159.54)        | -47%         |
| **Average Daily Transactions**     | 16.45              | 9.74               | $(6.71)            | -41%         |
| **Average Transaction Value (ATV)**| $150.16            | $134.50            | $(15.66)           | -10.4%       |

### Most Common Complaints (Total Complaints: 14)

| **Ref** | **Complaint Type**                 | **Quantity** | **%**  |
|---------|------------------------------------|--------------|--------|
| 1       | Checkout Issues                    | 6            | 42.9%  |
| 2       | Website Design/Layout Issues       | 4            | 28.6%  |
| 3       | Website Performance                | 1            | 7.1%   |
| 4       | Navigation/Product Info            | 2            | 14.3%  |
| 5       | Payment Options                    | 1            | 7.1%   |

**Conclusion:**  
The sales decline and negative feedback are primarily driven by:  
1. **Checkout Issues (42.9%)**: Mandatory registration (implemented in the redesign) and complex steps causing cart abandonment.  
2. **Unpopular Redesign (28.6%)**: Confusing layout and navigation.  
3. **Slow Website (7.1%)**: Poor loading speeds due to unoptimized images.  
4. **Navigation/Product Info Issues (14.3%)**: Difficulty finding products.  
5. **Limited Payment Options (7.1%)**: Lack of digital wallets.  

**Recommendations:**  
- **Simplify Checkout:** Add guest checkout and reduce steps.  
- **Redesign Layout:** Test prototypes with users via A/B testing.  
- **Optimize Speed:** Compress images and fix scripts.  
- **Enhance Navigation:** Improve search and categories.  
- **Add Payment Methods:** Integrate PayPal/Apple Pay.  

---

## DELIVERABLE 2: Root Cause Analysis Questions

### Key Questions:
1. Why did sales drop by 43% in March 2024?  
2. Why has cart abandonment increased post-redesign?  
3. Why was mandatory user registration enforced during checkout?  
4. Why were usability tests skipped before launching the redesign?  
5. Why was customer convenience overlooked in decision-making?  

**Root Cause:**  
A rushed checkout redesign prioritizing data collection over user experience led to frustration, abandonment, and revenue loss.

---

## DELIVERABLE 3: User Role Analysis

| **User Role**             | **Role Description**                          | **Key Requirements**                      |
|---------------------------|-----------------------------------------------|--------------------------------------------|
| **Guest User**            | Browses without an account                    | - Guest checkout<br>- Fast navigation      |
| **Registered Customer**   | Has an account for repeat purchases           | - Saved preferences<br>- Order tracking    |
| **Admin/Website Manager** | Manages site performance and security         | - Analytics tools<br>- Quick bug fixes     |
| **Marketing Team**        | Runs promotions and campaigns                 | - Customer segmentation<br>- ROI data      |
| **Sales Manager**         | Oversees revenue and growth                   | - Sales dashboards<br>- Cart analysis      |
| **Customer Support Team** | Resolves user issues                          | - Issue tracking<br>- Knowledge base       |

---

## DELIVERABLE 4: Stakeholder Analysis and Mapping

### Stakeholder Overview

| **Stakeholder**          | **Interest** | **Influence** | **Key Expectations**                    |
|--------------------------|--------------|---------------|-----------------------------------------|
| Guest User               | Low          | Low           | Quick checkout, no registration         |
| Registered Customer      | High         | Medium        | Personalized experience, loyalty rewards|
| Admin/Website Manager    | Medium       | **High**      | Site stability, security, scalability   |
| Marketing Team           | High         | Medium        | Accurate data for campaigns             |
| Sales Manager            | High         | High          | Increased conversion rates              |
| Customer Support Team    | Medium       | Low           | Efficient issue resolution              |

### Power-Interest Grid

|                          | **High Power**       | **Low Power**        |
|--------------------------|----------------------|----------------------|
| **High Interest**        | Sales Manager        | Registered Customer  |
| **Low Interest**         | Admin/Website Manager| Guest User, Support  |

---

## DELIVERABLE 5: RACI MATRIX

| **Task**                          | Guest User <br> *(Non-registered visitor)* | Registered Customer <br> *(Loyalty member)* | Admin/Website Manager <br> *(Technical lead)* | Marketing Team <br> *(Campaigns & data)* | Sales Manager <br> *(Revenue focus)* | Customer Support <br> *(Issue resolution)* |
|-----------------------------------|----------------------------|----------------------------|----------------------------|----------------------------|----------------------------|----------------------------|
| **1. Identify website issues**    | I                          | C                          | R                          | C                          | A                          | C                          |
| **2. Prioritize requirements**    | I                          | C                          | A                          | C                          | C                          | I                          |
| **3. Redesign checkout process**  | I                          | C                          | R                          | A                          | C                          | I                          |
| **4. Conduct usability tests**    | C                          | C                          | R                          | I                          | A                          | C                          |
| **5. Develop new features**       | I                          | I                          | A                          | C                          | C                          | I                          |
| **6. Launch redesigned website**  | I                          | I                          | A                          | C                          | I                          | I                          |
| **7. Monitor post-launch metrics**| C                          | C                          | R                          | I                          | I                          | A                          |

**Legend:**  
- **R (Responsible):** Executes the task.  
- **A (Accountable):** Approves and owns the outcome.  
- **C (Consulted):** Provides input before action.  
- **I (Informed):** Notified after completion.


---

## Final Recommendations

### Immediate Actions:
- **Roll back mandatory registration** until guest checkout is implemented.  
- **Initiate A/B testing** for the redesigned layout.  

### Long-Term Strategies:
- Build a **continuous feedback loop** with users.  
- Train the support team to handle **checkout-related queries**.  

### Next Steps:
- Schedule a **review meeting** with stakeholders.  
- Develop a **timeline** for image optimization and A/B testing.  
