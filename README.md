# Starbucks-Project

This is a caspstone project offered by Udacity. This project uses data provided by Starbucks to mimic the behaviour of the customer while using Starbucks rewwards mobile app. Starbucks sends offers to users via the mobile app. The offer can either be an adevertisment, a discount or BOGO (buy one get one free). There are three datasets provied by Starbucks. Each dataset contains different information aiming to describe how a customer responds to an offer. The aim of the project is combine these three datasets to see how different demographic groups respond which offer type. 

# Datasets

**Portfolio.json **

- id - offer id 
- offer_type - type of offer ie BOGO, discount, informational 
- difficulty - minimum required spend to complete an offer
- reward - reward given for completing an offer
- duration - time for offer to be open, in days
- channels 

**Profile.json **

- age - age of the customer
- became_member_on - date when customer created an app account
- gender - gender of the customer 
- id - customer id
- income - customer's income

**Transcript.json **

- event - record description (ie transaction, offer received, offer viewed, offer completed)
- person - customer id
- time - time in hours since start of test. The data begins at time t=0
- value - either an offer id or transaction amount depending on the record



# Libaries 
- pandas 
- numpy
- math 
- seaborn 
- matplotliib
- json


# Summary

- Only knearest neighbour classifier have not scored 100% accuracy. 
- The company should send more offers to females as they have completed more offers than males. 
- The company should target more average income customers and those between 41 and 60 years old. 
- Customers prefer BOGO offer types than discount offer types. 
