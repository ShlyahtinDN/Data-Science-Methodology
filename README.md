# Data-Science-Methodology

## Data Methodology Case Study
I choose credit cards
### 1. Description of the problem

I once became a victim of scammers. My mother-in-law had their bank card and PIN code stolen. Scammers have withdrawn a small amount from different ATMs until they have chosen a limit. We found out about it late and lost a lot of money.

I very much regretted that the bank does not have any verification of transactions for suspicious and attempts to suspend transactions until the person is confirmed.

I think this problem can be solved by examining typical user behavior and identifying deviations. In case of suspicious operation, request additional permission or slow down transactions.

### 2. Data Requirements
To do this, we need to collect data about customer transactions. We need to know the client's id, address, time, amount, money spent on, ATM or store address, type of online store.

### 3.Data Collection

Credit card information should be in a structured form. There will be a lot of data, and primary data aggregation may be required.

### 4. Understanding and preparing data
Some of the data may be incomplete, so we have to find out if necessary or we may skip it. Some other information may represent the same product under different names, so we would like to fix this. There will be a lot of information in the product database about various small transactions that we do not need, while looking through the records we should focus on the ones that we want to analyze. Then we have to delete unnecessary data. We will need to design a large number of columns with the same data for all clients. The columns will contain information with numerical coefficients that will characterize the client's behavior. For example, morning, day, night and the number of client transactions during these periods per month. Or, for example, how far the transactions are made from the place of residence. There will be many columns with types of purchases and the frequency and magnitude of these purchases.

### 5. Modeling and Evaluation

I propose to develop an analytical model that will classify bank card users and identify typical behavior for them. To do this, it will be necessary to try out various learning algorithms for classifying customers. For example the nearest neighbors method. Deep learning models will probably work well.
As a result, on the training data, we must achieve a high probability indicator and learn to understand that the transaction does not correspond to the typical client behavior.

### 6. Deployment and feedback
We have to publish the model and get feedback to understand how to improve it, what data is missing. We must try to minimize false positives.
