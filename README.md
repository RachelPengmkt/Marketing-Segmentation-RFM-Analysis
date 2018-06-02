# RFM Analysis - Customer Segmentation
### * What is "CustomerSegmentationRFM.ipynb" about?
	 - Python code using RFM model to segment customers
	 - You can use it to perform RFM anlaysis to segment customers based on their purchase history
     - This is a part of a project I'm working on for a research group @ U of Chicago 
### * What is RFM analysis?
     - RFM (Recency, Frequency, Monetary) analysis is a proven marketing model for behavior based customer segmentation. It groups customers based on their transaction history – how recently, how often and how much did they buy.
     - Please read details about RFM model here: https://www.putler.com/rfm-analysis/
### * What data would you need to perform RFM analysis using this Python code?
	- Recency: days since last purchase
	- Frequency: times of transactions per customer
	- Monetary: toal money spent per cusotmer 
### * What the input and output of this Python code?	
	- Input: a csv order file containing each order's purchase day and value per customer
	- Output: 
		- Top 10 cusotmers sort by RFM score and monetary
		- a csv file returing RFM score and relevant metrics per customer
    