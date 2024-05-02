# London-Borough-of-Barnet-Credit-card-report-for-Auditor-with-visualization
The four dataset here contain corporate credit card transactions published by the London Borough of Barnet for different time periods. Here we are genereting a report with visualization as asked by the auditor.


The 4 datasets here ( https://open.barnet.gov.uk/dataset/ep8y2/corporate-credit-card-transactions ) contain corporate credit card transactions published by the London Borough of Barnet for different time periods. Please make the following assumptions: 
•	Service Area denotes the functional areas (org chart) within the Borough of Barnett
•	Account Description is the name of the general ledger account in which each transaction is recorded
•	Assume that Journal Date and Transaction Date are synonymous
•	Disregard JV Date
•	Assume Total and JV Value are synonymous; these are the amount of each transaction
Consider your client to be an Auditor. These are their requirements: 
1.	The Auditor would like to get a summary view of the transactions for each Service Area. The summary view would include at least one visual representation of the transactions in such a way that they could compare them by quarter. Quarters are defined based on the calendar year (Q1 is January to March, Q2 April to June, etc.). The Auditor would also like a summary table with some relevant statistics (The Auditor says something along the lines of “transaction counts and averages”, but welcomes ideas). 

2.	The Auditor would like to get a view if there are any significant changes in spending behavior by Service Area and by Account. Changes in behavior could be spikes, but could also be permanent increases in the transaction amounts. Please identify instances of both or show that they do not exist in the data. 

3.	The Auditor would like to get an understanding of how Creditors are classified into accounts. In particular, they are worried about transaction misclassification. Are you able to identify instances in which Creditors are not consistently classified into Accounts (e.g., most of the time Creditor “AirTickets.com” is classified into “Travelling Expenses”, but on some occasions it is also found in “Miscellaneous”)? 

4.	In terms of spending behavior (defined by the number and the typical size of transactions), are there Service Areas that behave similarly and can be grouped together? How?

5.	The auditor has heard that you may know anomaly detection techniques. They would like to ask you for a sample of a few hundred transactions that are anomalous, different or worthwhile inquiring about.  The sample should include at least five transactions for each Service Area. Please provide this sample and explain why they are special or different.

