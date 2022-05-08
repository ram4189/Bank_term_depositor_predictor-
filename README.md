
# Bank marketing data analysis with term depositor prediction 

This is the classic marketing bank dataset uploaded originally in the UCI Machine Learning Repository. The dataset gives you information about a marketing campaign of a financial institution in which you will have to analyze in order to find ways to look for future strategies in order to improve future marketing campaigns for the bank.



# Conclusions

- Major disbalance in the data.
- Marital status wise data distribution for term depositors vs non depositors.
- Term depositors contribution marital status wise.
- Out of people making term deposit single and married are the major contributors.
- Majority of term depositors are from early 30+ ages.
- for both term depositors vs non depositor we have 0 balances.
- Term desposits are mostly from people who dont have any loan or housing.
- Most busy months are April, May, June, July and August.
- Term depositor calls are longer than non term depositors.
- Mostly pdays are -1 which means customers were not called, however to save some data we have considered pdays<=60.
- Management and retired class of people tend to have higher balances may be due to higher salary or post retirement savings.
- people with tertiary class of education, seems that have more balance -- may be due to higher income. Also more people are there with secondary and primary education due to large bandwidth that the graphs are showing.
- Average balance of retired and management customers who opted for term deposit are on the higher side even after having some or other liabilties.
- Term depositors tend to maintain Higher balance.
- Call duration for term depositor is higher usually.
- Y is strongly postively related with duration of the call made to attract customers.
- We have tried many models here and Xgboost has perfomed well with 0.92 roc auc score however FN is generally high for all of them which is not good (meaning that large numbers of prospect customers are predicted to be non prospect).
- I feel that getting more data from depositor section can bring some good results since high disbalance in the data.


# Advice to Bank from a data analyst on future decisions

- Please try to get more data if possible. call Conversation with the customer if possible to analyze the call data. If transcripts are available well and good and then we can analyze the text data to infer their sentiment on whether they are interested to go for the investment or not.
- As per the above analysis, high balance individual tend to invest more, so first target more and more customers with high balance, These could be one working into management or retired as these people have saved money and might want to regrow thier money.
- Second Please make more and more calls to customers since data above says majority of the customers were never called whereas large call durations is the determining factor here in predicting whether customers will make term deposit.
- Overall run a campaign to target customers with high balance [more in the age range 30+] by making multiple calls to them.
- If possible, maintain a good competitive lending rate with periodic rewards in various forms.
- Advertise about the program on different social media platform. Also bring educative sessions to attract more and more customers.



## 🚀 About Me
I'm a data analyst and love to deal with data ...

## Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Example Color | ![#0a192f](https://via.placeholder.com/10/0a192f?text=+) #0a192f |
| Example Color | ![#f8f8f8](https://via.placeholder.com/10/f8f8f8?text=+) #f8f8f8 |
| Example Color | ![#00b48a](https://via.placeholder.com/10/00b48a?text=+) #00b48a |
| Example Color | ![#00d1a0](https://via.placeholder.com/10/00b48a?text=+) #00d1a0 |


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.



