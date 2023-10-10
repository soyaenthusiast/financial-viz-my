## :thought_balloon: Background
This repository includes a sample PowerBI dashboard that I have built for a client to view and analyse their yearly, monthly and daily ***personal*** financial data. The user uses an iOS app to track all their daily expenses and exports the data via a .csv file from the app.

_FYI: Client is from Malaysia and hence the currencies, purchasing power, spend, and other economic terms are in the scope of a Malaysian living in Klang Valley_

## :eye_speech_bubble: Problem Statement
Issue arises when the user would like to view the data in a more constructed and efficient manner as the visuals and analysis provided in the built in-app is insufficient. These issues includes, but not limited to:
* Spend comparison between last month and this month on a daily granularity
* Net worth classifications
* Customising spend categories under (need, wants and savings)
* Easily track big anomaly spend by giving a MoM comparison

## :dizzy: Methodology
Extract the .csv file from the source (iOS financial tracking app), load it into PowerBI and do data magic :smiley:
Data magic includes, but not limited to:
* Data engineering, modelling and manipulation in Power Query Editor (PQE)
* DAX Calculations (ranging from beginner to intermediate levels - mainly the bridge between beginner-intermediate)
* Effective visuals

## :100: Conclusion and Future Work
Note: Data has been filtered to remove any confidential details of the user for privacy reasons. As such, you may use this PowerBI report to get an idea on how you may develop your DAX calculations to do some of the previous year (PY), last month (LM), this month (TM), etc calculations.

The client uses this dashboard on a weekly basis to view their financial performance and analyse if they are overspending (if necessary). Immensely helped the client to understand where their biggest spend comes from and where they can reduce it. 

Future improvements to be done:
* Include in predictive models to predict future spend/savings (e.g. 3 month moving average method)
* Automate data acquisition (at the moment, the source data is updated on a manual basis)
