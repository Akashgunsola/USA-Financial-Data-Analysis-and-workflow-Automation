# USA Financial Data Analysis and Workflow Automation

## Automating Financial Data Pipelines & Driving Credit Strategy Insights

## 1. Context of the case study based project

A financial analytics team processing U.S. survey data faced a daily operational bottleneck:

*   ~25 files received via email at 3 PM  
*   Insights required by 8 PM  
*   Fully manual workflow (download → merge → clean → analyze)

### Challenges:
*   Significant delays  
*   High error rates  
*   $12,000/month additional labor cost  
*   Reduced bandwidth for other projects  


## 2. What I Did

I replaced the entire manual workflow with an automated data pipeline and built a decision-focused dashboard.

### Core Contributions:
*   Eliminated manual data ingestion  
*   Built an automated ETL pipeline  
*   Designed analytical models for customer segmentation  
*   Delivered actionable insights for credit strategy  



## 3. System Design & Tech Stack

### Tech Stack:
*   **Email Client:** Microsoft Outlook 
*   **Workflow Automation:** Power Automate
*   **Cloud Storage & API:** Used Google Cloud Platform to create an API. Connected the Google Drive folder and Power BI using a Python script.
*   **Data Engineering/Scripting:** Python (Google Drive API integration, Combining multiple files and loading the new dataset into the Power Bi)
*   **Business Intelligence:** Power BI, Power Query (M Language), DAX

### Pipeline Flow:

**Before:** Manual → fragmented → error-prone  
**After:** Automated → centralized → scalable  

*   **Outlook Rules** → auto-filter incoming emails  
*   **Power Automate** → extract attachments  
*   **Google Drive** → centralized storage  
*   **Python** → data consolidation  
*   **Power Query** → transformation  
*   **Power BI** → automated dashboard  



## 4. Key Business Insights

### Insight 1: Income ≠ Payment Discipline
*   Avg income: **$159K**
*   Avg delay: **21 days**

**Conclusion:** Customers have the ability to pay but lack repayment discipline.  
**Action:** Use behavioral nudges and penalties instead of restricting credit.



### Insight 2: Credit Growth is Age-Driven
*   Peak credit expansion: **18–25**
*   Declines after: **45+**

**Conclusion:** Younger users drive credit growth.  
**Action:** Target early-age customers for credit expansion and shift older users to wealth products.



### Insight 3: Credit Demand is Highest Among Younger Users
*   Teens and young adults show the highest credit enquiries.  
*   Older users show minimal activity.  

**Conclusion:** Demand for credit decreases with age.  
**Action:** Focus acquisition strategies on younger segments.



### Insight 4: Two High-Value Customer Segments
*   Early segment: **14–18**
*   Prime segment: **28–40**

**Conclusion:** 
*   Younger users are aspirational.  
*   Mid-age users are financially ready.  

**Action:** Use segmented marketing strategies instead of a generic approach.



### Insight 5: Mid-Age Group Drives Revenue
*   Peak loan usage: **40–50**
*   Highest population: **25–40**

**Conclusion:** This segment generates the highest revenue.  
**Action:** Prioritize loans and premium financial products.



### Insight 6: Credit Quality Drives Spending Behavior
*   Good credit → high-value transactions.  
*   Bad credit → low-value, inconsistent payments.  

**Conclusion:** Low credit users are both risky and low-value.  
**Action:** Focus on retaining high-quality customers.


### Insight 7: High Payday Loan Usage (Risk Indicator)
*   Payday loans are among the most common.  

**Conclusion:** Indicates financial instability in the customer base.  
**Action:** Introduce structured loan alternatives.



### Insight 8: LTV is Multi-Factor Driven
*   High-value customers exist across different ages.  

**Conclusion:** Age alone is not a reliable predictor of value.  
**Action:** Use multi-variable segmentation (income + behavior + credit score).

---

## 5. Business Impact
By replacing a highly manual data consolidation process with a Python and Power BI architecture, this project:
*   **Eliminated daily workflow bottlenecks,** ensuring the 8 PM reporting deadline is consistently met.
*   **Potentially Saved several dollars per month** in redundant labor costs.
*   **Removed human error** from the data manipulation phase.
*   **Shifted focus** from data wrangling to high-value credit strategy and actionable decision-making.

# 6. **Conclusion**
This project shows how automation can make data workflows faster and more accurate. It reduced manual work and improved reporting efficiency.
