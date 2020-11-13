# Online-Retail-Customer-Segmentation

This project aims to understand the value derived from different customers segments. The dataset contains features like customerID, Quantity, Stockcode etc. of
the individuals. Used clustering technique to identify customer behaviors. Provided valuable insights into the wider business based on the segments generated. RFM reduced the marketing costs due to optimize targeting.

## Attribute Infromation

InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
Description: Product (item) name. Nominal.
Quantity: The quantities of each product (item) per transaction. Numeric.
InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
UnitPrice: Unit price. Numeric, Product price per unit in sterling.
CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
Country: Country name. Nominal, the name of the country where each customer resides.

Dataset link: http://archive.ics.uci.edu/ml/datasets/online+retail


Customer Segmentation: It is a methodology using which we can divide our customer base into group of individuals who are similar in terms of either gender, spending behavior, 
frequency to vist, age or other demographics.

Customer segmentation allows companies to precisely target the customers who has a specific needs and desires. This way companies can desire the targeted campaigns to the right group or audience it may also be the case that during the creation of these individuals groups or clusters, company might identify new market segments on which company can focus more as it might be more lucrative also using segmentation companies can identify groups that require extreme attention such that people in that group are on the verge of churning out. 

There may be as group of customers or segments who has a highest potential value it can also help with created targeted startegies that can capture your customers attention and create positive high-value experiences with your brand's. 

So, in a nutshell we cann perform segmentation based on our business requirements here to perform customer segmentation we will first utilize RFM Modelling to calculate the RFM Scores for each customers and then we will apply Unsupervised Machine Learning technique called K-Means to group those customers into different groups based on RFM Scores calculated. 

## RFM segmentation

RFM segmentation is a great method to identify groups of customers for special treatment. Learn how to use this method to improve your customer marketing.

RFM segmentation allows marketers to target specific clusters of customers with communications that are much more relevant for their particular behavior – and thus generate much higher rates of response, plus increased loyalty and customer lifetime value. Like other segmentation methods, RFM segmentation is a powerful way to identify groups of customers for special treatment. RFM stands for recency, frequency and monetary – more about each of these shortly.

Marketers typically have extensive data on their existing customers – such as purchase history, browsing history, prior campaign response patterns and demographics – that can be used to identify specific groups of customers that can be addressed with offers very relevant to each.

While there are countless ways to perform segmentation, RFM analysis is popular for three reasons:

1) It utilizes objective, numerical scales that yield a concise and informative high-level depiction of customers.
2) It is simple – marketers can use it effectively without the need for data scientists or sophisticated software.
3) It is intuitive – the output of this segmentation method is easy to understand and interpret.
