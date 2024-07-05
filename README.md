# RFM-Analysis
Using python to segment customers according to RFM model
## 1. Introduction
### 1.1 Business question
- SuperStore Company is a global retail company with a large customer base. For the upcoming Christmas and New Year season, the Marketing department intends to launch marketing campaigns to appreciate customers who have supported the company over time, as well as to target potential customers who could become loyal patrons.
- However, the Marketing department hasn't yet segmented this year's customers because the dataset is too vast to handle manually, unlike in previous years. They are seeking assistance from the Data Analytics department to implement a customer segmentation task to tailor marketing campaigns to different customer groups.
- With the retail model of Superstore company, which indicator should be most focused in the 3 indicators R,F, and M?
### 1.2 Dataset
This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.
InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'C', it indicates a cancellation.
StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
Description: Product (item) name. Nominal.
Quantity: The quantities of each product (item) per transaction. Numeric.
InvoiceDate: Invoice Date and time. Numeric, the day and time when each transaction was generated.
UnitPrice: Unit price. Numeric, Product price per unit in sterling.
CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
Country: Country name. Nominal, the name of the country where each customer resides.
Transaction dataset
![image](https://github.com/BuiDucPhat12/RFM-Analysis/assets/174614831/1d4b3f91-2164-47cf-8f24-4df23b8c9b33)

## 2. Method: RFM Analysis
- RFM is a method used for analyzing customer value. It commonly used in database marketing and direct marketing and has received particular attention in retail and professional services industries
- RFM stands for:
1. Recency: How recently a customer made a purchase.
2. Frequency: How often a customer makes purchases.
3. Monetary Value: The total amount a customer has spent.
## 3.Insight
### Definition and recommended action for each customer segment:

| Segment | Characteristics | Recommendation |
| :-: | :-: | :-: |
| Champions | Bought recently, buy often and spend the most! | Reward them. Can be early adopters for new products. Will promote your brand. |
| Loyal | Spend good money with us often. Responsive to promotions. | Upsell higher value products. Ask for reviews. Engage them. |
| Potential Loyalist | Recent customers, but spent a good amount and bought more than once. | Offer membership / loyalty program, recommend other products. |
| New customers | Bought most recently, but not often. | Provide on-boarding support, give them early success, start building relationship. |
| Promising | Recent shoppers, but haven’t spent much. | Create brand awareness, offer free trials |
| Need attention | Above average recency, frequency and monetary values. May not have bought very recently though. | Make limited time offers, Recommend based on past purchases. Reactivate them. |
| About to sleep | Below average recency, frequency and monetary values. Will lose them if not reactivated. | Share valuable resources, recommend popular products / renewals at discount, reconnect with them. |
| At risk | Spent big money and purchased often. But long time ago. Need to bring them back! | Send personalized emails to reconnect, offer renewals, provide helpful resources. |
| Cannot lose them | Made biggest purchases, and often. But haven’t returned for a long time. | Win them back via renewals or newer products, don’t lose them to competition, talk to them. |
| Hibernating customers | Last purchase was long back, low spenders and low number of orders. | Offer other relevant products and special discounts. Recreate brand value. |
| Lost customers | Lowest recency, frequency and monetary scores. | Revive interest with reach out campaign, ignore otherwise. |
