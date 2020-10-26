# Decision Trees in Python

### Overview:
You work on the analytics team at a large investment bank. While many of the departments are analytically savvy, a portion of the sales team is just beginning to come out of the realm of telemarketing and into the digital age. They’ve collected data on some 45,000+ previous customers and would like to use that data to gather some guidance on how to know what product to suggest to current customers next. They are interested in sending out promotional information on 4 different products: Brokerage Accounts, Roth IRAs, Term Deposits (CDs), and Mortgage Refinance Offers. They would like some analytical guidance in order to determine which promotions to send to which individuals, but they are not ready to implement a fancy real-time model with software. They’re looking for simple rules to guide them in their marketing assignments.

### Initial Univariate EDA:
- Identified missing values (0.0097% of overall data) and decided to drop them 
- Divded variables into categorical and numeric
- Evaluated distribution of variables

### Model Building:
- Split data into train and test sets
- Compared gini and entropy for better accuracy
- Built preliminary decision tree with min of 20 observations per leaf
- Pruned tree to prevent overfitting

### Final Decision Tree:
<img src="images/decision tree.png" width=800>
