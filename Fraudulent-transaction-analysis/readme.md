# Fraudulent Transaction Analysis
## Features Overview
### Target Variable :

- isFraud -  This binary variable indicates whether a transaction is fraudulent (1) or not (0).

- This is the transactions made by the fraudulent agents inside the simulation. In this specific dataset the fraudulent behavior of the agents aims to profit by taking control or customers accounts and try to empty the funds by transferring to another account and then cashing out of the system.

### Independent variables : 

- step - maps a unit of time in the real world. In this case 1 step is 1 hour of time. Total steps 744 (30 days simulation).

- type - CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER.

- amount - amount of the transaction in local currency.

- nameOrig - customer who started the transaction

- oldbalanceOrg - initial balance before the transaction

- newbalanceOrig - new balance after the transaction

- nameDest - customer who is the recipient of the transaction

- oldbalanceDest - initial balance recipient before the transaction. Note that there is not information for customers that start with M (Merchants).

- newbalanceDest - new balance recipient after the transaction. Note that there is not information for customers that start with M (Merchants).

- isFlaggedFraud - The business model aims to control massive transfers from one account to another and flags illegal attempts. An illegal attempt in this dataset is an attempt to transfer more than 200.000 in a single transaction.

## EDA

### Fraud is Rare but Targeted

- Only 0.13% of all transactions are fraudulent.

- Fraud is not random—it occurs exclusively in TRANSFER and CASH-OUT transaction types.

### Fraud Pattern Identified

- Fraudsters typically transfer money from a compromised account and then immediately cash out.

- These transactions often involve large amounts and accounts with zero or low initial balances.

### Flagging Mechanism is Limited

- The current rule-based flagging system (flagging transactions over 200,000) misses many actual frauds and raises false alarms on legal large transactions.

- Less than 1% of flagged transactions are actual frauds.

- Behavioral Anomalies in Fraudulent Transactions

### Fraudulent transactions frequently show:

- No money received in the destination account (destination balance unchanged).

- Zero or depleted source balances post-transaction — indicating funds were drained.
