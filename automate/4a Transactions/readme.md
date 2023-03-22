# Transactions flow

An [Automate](https://llamalab.com/automate/) flow to run and manage financial transactions. The flow collects the following data for each transaction:

* Date
* Time
* Location
* Accounts (To and From)
* Item
* Item Type
* Item Group
* Brand
* Amount Spent
* Quantity
* Unit Cost
* Base Amount (in Euros)

## Components

The flow currently has a fibre to intialise the flow, a fibre to input transactions through a web interface, fibres to read and write to datalists (such as datalists for Item Group), a fibre to update the balance, and a fibre to handle recurring payments.