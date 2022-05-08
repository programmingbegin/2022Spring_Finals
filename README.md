# Monte Carlo simulation of the supply chain of a manufacturing company

Team members:

Pradyot Dutta GitHub: programmingbegin
Reethika Renganathan GitHub: reethika18

Project Idea: We plan to simulate a supply chain environment of an international automobile organization to identify whether it is more profitable to receive multiple smaller orders or to receive one larger order and to check if costs can be reduced by obtaining exact amounts from suppliers rather than ordering wholesale amounts every week.

Assumptions:
•	All products being delivered are of the same quality and usable
•	Organization is immediately notified of the delay/disruption to supply chain routes.
•	There are no significant events occurring in the headquarters under focus due to any events which are otherwise disrupting the supply chain.
•	The manufacturing inventory maintains the inventory from the previous order

Constant variable:
•	Inventory size
•	Travel time (normal conditions)
•	Manufacturing/Assembly time

Random Variables:
•	Delivery time 
•	Volume provided by suppliers
•	Order Quantity


References:
https://towardsdatascience.com/robust-supply-chain-network-with-monte-carlo-simulation-21ef5adb1722
https://data.usaid.gov/api/views/a3rc-nmf6/rows.csv?accessType=DOWNLOAD

1. Identify an optimum order quantity which fetches the highest profits.
2. We have made a cost optimization function where the suppliers are periodically providing the exact quantity needed by the manufacturer to the suppliers rather than a periodic fixed volume. Here we are checking if for a 1000 orders if this approach is more profitable and if we are able.to complete the order in time.  



