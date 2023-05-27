# **Customer Lifetime Value (CLV)**

![alt text](https://github.com/Cristhian-Ninanya/customer_lifetime_value/blob/main/Images/CLV_image.jpg?raw=true)

## **Overview**

Customer Lifetime Value (CLV) analysis is a crucial concept in marketing and customer relationship management. It helps businesses understand the long-term value that each customer brings to the company, enabling them to make data-driven decisions regarding customer acquisition, retention, and marketing strategies.

## **Target:**
By analyzing customer lifetime value, you can identify the most effective marketing channels and campaigns for acquiring high-value customers. Additionally, you can develop targeted retention strategies to keep these valuable customers engaged and loyal.

## **DataSet information:**

For this project we will use a dataset based on customers’ relationships with the business. This DataSet is stored in File "Data".

**Attribute Information:**

* **customer_id:** Customer Identification.
* **channel:** The various marketing and communication channels through which a company interacts with its customers.
* **cost:** The costs associated with acquiring and serving to customers.
* **conversion_rate:** Conversion rate refers to the percentage of potential customers who take a desired action, such as making a purchase, out of the total number of individuals who were exposed to a marketing campaign or visited a particular channel.
* **revenue:** Revenue refers to the total amount of money generated from sales or customer transactions within a specific period.

## Imported DataSet:

![alt text](https://github.com/Cristhian-Ninanya/customer_lifetime_value/blob/main/Images/dataframe.png?raw=true)

## Compare the cost of acquisition across different channels

![alt text](https://github.com/Cristhian-Ninanya/customer_lifetime_value/blob/main/Images/cust_acq_cost_channel.png?raw=true)

**OBS:**
* "**paid advertisement**" is the most expensive channel.
* "**email marketing**" is the least expensive channel.

## "conversion_rate" vs "channel

![alt text](https://github.com/Cristhian-Ninanya/customer_lifetime_value/blob/main/Images/conversion_rate_chann.png?raw=true)

**OBS:**
* "**Social media**" is the most effective channel for converting customers.
* "**paid advertising**" is the least effective channel for converting customers.

## Total revenue by channel

![alt text](https://github.com/Cristhian-Ninanya/customer_lifetime_value/blob/main/Images/total_revenue_chann.png?raw=true)

**OBS:**
* "**email marketing**" is the most profitable channel (27.3%) in terms of generating revenue.
* "**social media**" is the least profitable channel (22.3%) in terms of generating revenue.
* There is not a huge difference between the percentages of revenue generation.

## Return on investment (ROI) for each channel

$$ 
ROI = \frac{{revenue}}{cost} 
$$

![alt text](https://github.com/Cristhian-Ninanya/customer_lifetime_value/blob/main/Images/roi_chann.png?raw=true)

**OBS:**
* The ROI from **email marketing** is higher than all other channels.
* The ROI from **paid advertising** is the lowest.

## Customer Lifetime Value (CLV):

$$ 
CLV = (revenue - cost) * \frac{{conversion_-rate}}{cost} 
$$

![alt text](https://github.com/Cristhian-Ninanya/customer_lifetime_value/blob/main/Images/clv_channel.png?raw=true)

**OBS:**
* "**Social Media**" and "**referral**" channels have the highest CLV.
* "**Paid Advertising**" has the lowest CLV.

## CLV distribution of "social media" and "referral"

[alt text](https://github.com/Cristhian-Ninanya/customer_lifetime_value/blob/main/Images/clv_distr_chann.jpg?raw=true)

**OBS:**
* The Customer Lifetime Value from the "Social Media" channel is slightly better than the "referral" channel.

## **Observations:**

1. **Reduce investment in "paid advertising"**: Since it is the most expensive channel and has the lowest Return on Investment (ROI), it may be beneficial to reconsider the allocation of resources to this channel. By reducing investment in paid advertising, you can potentially allocate those resources to other channels with higher effectiveness and ROI.

2. **Increase investment in "social media"**: As mentioned, "social media" is identified as the most effective channel and has the highest Customer Lifetime Value (CLV). This suggests that allocating more resources and investment into social media marketing efforts could yield better results and contribute to the overall success of the business.

3. **Increase investment in "referral"**: The "referral" channel is highlighted as having the highest Customer Lifetime Value (CLV). This indicates that customer referrals can be a valuable source of new customers and revenue. Increasing investment in referral programs or strategies to encourage and incentivize customer referrals can be beneficial for long-term customer acquisition and retention.

4. By focusing on channels with **higher effectiveness**, **lower costs**, and **higher CLV**, you can optimize your marketing strategies and maximize the return on your marketing investments.
