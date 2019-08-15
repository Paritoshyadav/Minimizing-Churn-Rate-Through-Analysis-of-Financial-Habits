# Minimizing-Churn-Rate-Through-Analysis-of-Financial-Habits
Build a Machine learning model to direct customers to subscribe product through a app behavior analysis

# INTRODUCTION 
Subscription Products often are the main source of revenue for companies across all industries. These products can come in the form of a one size fits all' overcompassing subscription, or in multi-level memberships. Regardless of how they structure their memberships, or what industry they are in, companies almost always try to minimize customer churn (a.k.a. subscription cancellations). To retain their customers, these companies first need to identify behavioral patterns that act as catalyst in disengagement with the product. 
- **Market**: The target audience is the entirety of a company's subscription base. They are the ones companies want to keep. 
- **Product**: The subscription products that customers are already enrolled in can provide value that users may not have imagined, or that they may have forgotten. 
- **Goal**: The objective of this model is to predict which users are likely to churn, so that the company can focus on re-engaging these users with the product. These efforts can be email reminders about the benefits of the product, especially focusing on features that are new or that the user has shown to value. 

# BUSINESS CHALLENGE
- In this Case Study we will be working for a fin-tech company that provides a subscription product to its users, which allows them to manage their bank accounts (savings accounts, credit cards, etc), provides them with personalized coupons, informs them of the latest low-APR loans available in the market, and educates them on the best available methods to save money (like videos on saving money on taxes, free courses on financial health, etc). 
- We are in charge of identifying users who are likely to cancel their subscription so that we can start building new features that they may be interested in. These features can increase the engagement and interest of our users towards the product. 

# DATA
- By subscribing to the membership, our customers have provided us with data on their finances, as well as how they handle those finances through the product. We also have some demographic information we acquired from them during the sign-up process. • Financial data can often be unreliable and delayed. As a result, companies can sometimes build their marketing models using only demographic data, and data related to finances handled through the product itself. Therefore, we will be restricting ourselves to only using that type of data. Furthermore, product-related data is more indicative of what new features we should be creating as a company. 

# DATASET
Mock-up dataset based on trends found in real world case studies; 27 000 instances and 30 features (40 after creating dummy variables of categorical ones)

# Goal
Predict which users are likely to churn, so that the company can focus on re-engaging these users with the product.

# Algorithms uses:
- LR regularization L1 and L2 
- SVM classifier 
- GB classifier
- RF classifier
- Grid search

# Conclusion
Once I employed all these methods, we were able to utilize various machine learning metrics. Each model provided valuable insight. The best result is given by svm with hyperparameter using GridSearchCV and RF method
## Parameter uses
- `C: 15` 
- `gamma: 0.01`
- `kernel': 'rbf'`

# Result
After using best parameter from grid search and RFE we get accuracy of 68% 
