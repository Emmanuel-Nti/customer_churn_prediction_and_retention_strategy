# Customer Churn Prediction & Retention Strategy


| Project Description | Libraries Used | Source of Data |
| :---------------------- | :---------------------- | :---------------------- | 
| The gym chain Model Fitness is developing a customer interaction strategy based on analytical data. One of the most common problems gyms and other services face is customer churn. How do you know if a customer is no longer with you? You can calculate churn based on people who get rid of their accounts or don't renew their contracts. However, sometimes it's not obvious that a client has left: they may walk out on tiptoes. Churn indicators vary from field to field. If a user buys from an online store rarely but regularly, you can't say they're a runaway. But if for two weeks they haven't opened a channel that's updated daily, that's a reason to worry: your follower might have gotten bored and left you. For a gym, it makes sense to say a customer has left if they don't come for a month. Of course, it's possible they're in Cancun and will resume their visits when they return, but's that's not a typical case. Usually, if a customer joins, comes a few times, then disappears, they're unlikely to come back. In order to fight churn, Model Fitness has digitized a number of its customer profiles. My task is to analyze them and come up with a customer retention strategy. | *pandas*, *matplotlib.pyplot*, *numpy*, *standardScaler*, *sklearn*, *scipy*, *scikitplot*  | Practicum by Yandex |


## Description of Data

**The dataset includes the following fields:**

- `Churn:` the fact of churn for the month in question
- `gender:`
- `Near_Location:` whether the user lives or works in the neighborhood where the gym is located
- `Partner:` whether the user is an employee of a partner company (the gym has partner companies whose employees get discounts; in those cases the gym stores information on customers' employers).
- `Promo_friends:` whether the user originally signed up through a "bring a friend" offer (they used a friend's promo code when paying for their first membership).
- `Phone:` whether the user provided their phone number.
- `Age:`
- `Lifetime:` the time (in months) since the customer first came to the gym.
- `Contract_period:` 1 month, 3 months, 6 months, or 1 year.
- `Month_to_end_contract:` the months remaining until the contract expires.
- `Group_visits:` whether the user takes part in group sessions.
- `Avg_class_frequency_total:` average frequency of visits per week over the customer's lifetime.
- `Avg_class_frequency_current_month:' average frequency of visits per week over the preceding month.
- 'Avg_additional_charges_total:' the total amount of money spent on other gym services: cafe, athletic goods, cosmetics, massages, etc.
