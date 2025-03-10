# Banking_Term_Deposit_Subscriptions_Prediction

### Problem Statement
Direct marketing campaigns play a crucial role in the financial sector, helping institutions engage with potential clients and drive product subscriptions. In this project, we analyzed a dataset from a Portuguese banking institution’s direct marketing campaign, where phone calls were used to encourage clients to subscribe to term deposits. Since multiple contacts were made with the same clients, understanding the factors influencing their decision becomes essential.<br>
The objective of this study is to develop a predictive model that accurately determines whether a client will subscribe to a term deposit based on historical campaign data. By leveraging machine learning techniques, we aim to enhance the efficiency and effectiveness of marketing strategies, leading to improved customer targeting and resource allocation.

### Motivation
This project has practical implications for the banking and insurance sectors by enhancing marketing efficiency. A predictive model can help identify clients most likely to subscribe to term deposits, enabling more targeted outreach and resource optimization. Additionally, refining campaign strategies—such as messaging, timing, and contact frequency—can improve conversion rates and revenue. Furthermore, accurate predictions can support personalized investment planning, helping clients make informed financial decisions while benefiting the institution.

### Data Source
[UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/dataset/222/bank+marketing) <br>
The data pertains to direct marketing campaigns (phone calls) conducted by a Portuguese banking institution. The objective of classification is to predict whether the client will opt for a term deposit or not. It is an imbalanced dataset with 45,211 rows and 16 columns which contains basic client data, social and economic attributes and other information

### Methodologies Used
At First Feature Selection (Select KBest, RFECV) is implemened followed by these algorithms
1. Class balancing techniques (Random Over Sampling, SMOTE, ADASYN, Border Line SMOTE)
2. KNN
3. SVM
4. Logistic Regression
5. Decision Tree
6. Random Forest
7. Ensemble Learning ( Boosting)
And Finally Hyperparamter Tuning using Grid Search
