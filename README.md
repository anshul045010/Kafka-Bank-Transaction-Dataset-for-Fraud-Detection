# BANK TRANSACTIONS ANALYSIS

### OBJECTIVE 
Understand Customer Behavior: Analyze transaction data to gain insights into customer spending habits, preferences, and risk profiles.
Optimize Operations: Improve service delivery, channel utilization, and resource allocation based on customer behavior and transaction patterns.
Enhance Fraud Detection: Develop models and strategies to detect and prevent fraudulent activities.
Improve Customer Experience: Enhance customer satisfaction by optimizing service delivery channels and addressing customer needs based on their behavior.
Develop Targeted Strategies: Develop targeted marketing campaigns, product offerings, and risk management strategies based on customer demographics and transaction behavior.

### INTRODUCTION
In today's digital age, financial institutions are faced with the challenge of managing a vast amount of transaction data. This data holds invaluable insights into customer behavior, market trends, and potential risks. This project aims to leverage the power of data analytics to gain a deeper understanding of customer behavior and identify key trends within a set of bank transaction data.
Through exploratory data analysis and visualization techniques, we will investigate various aspects of customer activity, including transaction patterns, channel preferences, spending habits, and demographic characteristics. The insights gained from this analysis will be used to inform business decisions, improve customer experience, enhance fraud detection capabilities, and optimize operational efficiency.


This project will contribute to a better understanding of customer needs and preferences, ultimately enabling the bank to provide more personalized and efficient services while mitigating potential risks.

### DATASET: BANK TRANSACTION DATASET

https://www.kaggle.com/datasets/valakhorasani/bank-transaction-dataset-for-fraud-detection

<img width="929" alt="8" src="https://github.com/user-attachments/assets/ecf2971d-4aad-41e8-966d-d9ac8668a970" />

**Number of rows:** 2,512

**Number of columns:** 15

### VARIABLE DESCRIPTION

**1. TransactionID:** Unique alphanumeric identifier for each transaction.
 
**2. AccountID:** Unique identifier for each account, with multiple transactions per account.

**3. TransactionAmount:** Monetary value of each transaction, ranging from small everyday expenses to larger purchases.

**4. TransactionDate:** Timestamp of each transaction, capturing date and time.

**5. TransactionType:** Categorical field indicating 'Credit' or 'Debit' transactions.

**6. Location:** Geographic location of the transaction, represented by U.S. city names.

**7. DeviceID:** Alphanumeric identifier for devices used to perform the transaction..

**8. IP Address:** IPv4 address associated with the transaction, with occasional changes for some accounts.

**9. MerchantID:** Unique identifier for merchants, showing preferred and outlier merchants for each account.

**10. AccountBalance:** Balance in the account post-transaction, with logical correlations based on transaction type and amount.

**11. PreviousTransactionDate:** Timestamp of the last transaction for the account, aiding in calculating transaction frequency.

**12. Channel:** Channel through which the transaction was performed (e.g., Online, ATM, Branch)..

**13. CustomerAge:** Age of the account holder, with logical groupings based on occupation.

**14. CustomerOccupation:** Occupation of the account holder (e.g., Doctor, Engineer, Student, Retired), reflecting income patterns.

**15. TransactionDuration:** Duration of the transaction in seconds, varying by transaction type.

**16. LoginAttempts:** Number of login attempts before the transaction, with higher values indicating potential anomalies.

### DASHBOARD 
https://github.com/user-attachments/assets/514a9143-09de-4a6e-8619-1e5d04b1e1e5

### CHARTS

Certainly! Here are the observations and insights for graphs in a concise format, with added data:

<img width="601" alt="Screenshot 1" src="https://github.com/user-attachments/assets/7d115d7f-dda4-4fbd-b95f-6ce239ca92cd" />

**Average Customer Age For Different Occupation**

**Observation:** The "Retired" group has the highest average customer age (65 years), followed by "Doctor" (45 years), "Engineer" (38 years), and "Student" (22 years).

**Insights:** This graph highlights how customer demographics can vary significantly based on their occupation. This information could be valuable for targeted marketing campaigns or product offerings tailored to specific age groups within each occupation. For instance, financial products geared towards retirement planning might be more relevant for the "Retired" group, while those focused on student loans or savings for future education could be more suitable for the "Student" group.

**Geographic Transaction Intensity**

**Observation:** "Branch" transactions have the highest intensity in "El Paso", followed by "Online" transactions in "Austin". "ATM" transactions are most frequent in "Detroit".

**Insights:** This graph provides valuable insights into regional transaction patterns and channel preferences. Businesses can leverage this information to optimize their branch network and ATM placements. For example, if a particular location shows high online transaction intensity, the bank could focus on enhancing its online banking services and security measures in that region. Conversely, if a location has a high volume of branch transactions, it might be beneficial to increase staffing or expand the branch's physical space.

<img width="610" alt="Screenshot 2" src="https://github.com/user-attachments/assets/2e95750c-f0b0-4687-8f59-1f43bba67c59" />

**Transaction Type Proportion**

**Observation:** Debit transactions constitute the vast majority (around 76.5%) of all transactions.

**Insights:** This indicates a spending-oriented market with a higher volume of debit transactions compared to credit transactions. This information is crucial for understanding overall financial activity and implementing strategies for managing risk and promoting financial health. For example, banks can use this information to allocate resources for fraud prevention and customer support accordingly.

**Location based on Transaction Amount**

**Observation:** Locations like El Paso and Austin exhibit higher average transaction amounts compared to Phoenix and Las Vegas.

**Insights:** This variation in spending patterns across locations highlights regional differences in economic activity and consumer behavior. Businesses can leverage this information to optimize their marketing strategies, resource allocation, and risk management efforts by tailoring their approaches to the specific spending patterns of each region. For example, banks in El Paso might focus on offering higher credit limits or more sophisticated investment products to cater to the higher spending activity.

<img width="608" alt="Screenshot 3" src="https://github.com/user-attachments/assets/76d16986-abb1-4069-aced-3ee085b5e11b" />

**Longest Transaction Duration by Occupation**

**Observation:** Doctors have the longest average transaction duration (300 seconds), followed by Students (299 seconds), Retired individuals (296 seconds), and Engineers (233 seconds).

**Insights:** This data suggests that transactions performed by Doctors tend to take longer to complete, possibly due to the complexity of their financial transactions or the need for more in-depth consultation with bank representatives. This information could be valuable for optimizing service delivery and improving customer experience for this demographic. For example, banks could allocate more time for transactions involving Doctors or provide alternative channels that minimize wait times, such as dedicated phone lines or online banking features optimized for complex transactions.

**Login Attempts with Average Transaction Amount**

**Observation:** The scatter plot shows a general trend where higher average transaction amounts are associated with a greater number of login attempts. For instance, transactions with an average amount exceeding $10,000 often require 3 or more login attempts, while transactions below $5,000 typically involve 1 or 2 attempts.

**Insights:** This data indicates a potential correlation between the complexity or security level of a transaction and the number of login attempts required. This information can help banks identify potential security risks and implement measures to streamline the login process for high-value transactions. For example, banks could consider implementing multi-factor authentication only for transactions exceeding a certain threshold, while maintaining a simpler login process for smaller transactions.

<img width="608" alt="Screenshot 4" src="https://github.com/user-attachments/assets/22923ce0-6ff8-40ee-b6c5-a2d7a21a70b6" />

**Total Transaction Amount by Merchant**

**Observation:** Merchant M093 has the highest total transaction amount, with a significant portion falling in the 4,500-6,000 range.

**Insights:** This graph indicates that Merchant M093 is a major contributor to the overall transaction volume and revenue. Analyzing this merchant's category and customer demographics can provide valuable insights for marketing and business development strategies. Additionally, monitoring transactions with this merchant is crucial for fraud detection and risk management.

**Transaction Duration For Each Channel**

**Observation:** ATM transactions have the shortest median duration, followed by Online and Branch transactions.

**Insights:** This graph suggests that ATM transactions are generally quicker compared to online or branch transactions. This information can be used to optimize service delivery and improve customer satisfaction across different channels. For example, banks can focus on streamlining ATM processes to further reduce transaction times and enhance customer experience. Additionally, this data can inform staffing decisions and resource allocation for branch operations.

<img width="608" alt="Screenshot 5" src="https://github.com/user-attachments/assets/e00637c3-3145-48ec-86d7-5c1ab3f1d977" />

**Account Balance Post Transaction**

**Observation:** The average account balance fluctuates significantly over the observed timeframe, with a peak around 17:21:00.

**Insights:** This graph suggests dynamic account activity with substantial changes in account balances occurring within a short period. Further analysis could reveal the underlying reasons for these fluctuations, such as large deposits, withdrawals, or transfers. This information is crucial for understanding customer behavior and optimizing financial services.

**Devices Used for High Value Transactions**

**Observation:** Devices D000377, D000032, and D000697 are associated with the highest transaction amounts.

**Insights:** This graph identifies specific devices used for high-value transactions. This information can be used to enhance fraud detection and prevention measures. For example, by monitoring transactions from these devices closely, banks can detect and prevent potential fraudulent activity. Additionally, this information can be used to improve customer service by providing tailored support for high-value transactions.

<img width="609" alt="Screenshot 6" src="https://github.com/user-attachments/assets/116ce9cf-d975-4e8f-9286-b363c4522f3a" />

**Transaction Duration Trends**

**Observation:** The average transaction duration fluctuates over time, with some periods showing higher durations than others.

**Insights:** This graph reveals dynamic trends in transaction processing times. Analyzing these fluctuations can help identify potential bottlenecks or operational inefficiencies. For example, a sudden increase in average transaction duration might indicate system issues, staffing shortages, or changes in transaction complexity. Understanding these trends is crucial for optimizing service delivery and maintaining a positive customer experience.

**Total Transaction Amount by Transaction Type**

**Observation:** Debit transactions have a significantly higher total amount compared to Credit transactions.

**Insights:** This graph confirms a spending-oriented market with a higher volume of debit transactions. This information is crucial for understanding overall financial activity and implementing strategies for managing risk and promoting financial health. For example, banks can use this information to allocate resources for fraud prevention and customer support accordingly.

<img width="607" alt="Screenshot 7" src="https://github.com/user-attachments/assets/20d90def-68b1-4211-affe-3b0b3f402841" />

**Account Balance Trends**

**Observation:** The average account balance exhibits significant fluctuations over the observed timeframe, with periods of rapid increases and decreases.

**Insights:** This graph indicates dynamic account activity with substantial changes in account balances occurring within short periods. Further analysis could reveal the underlying reasons for these fluctuations, such as large deposits, withdrawals, or transfers. This information is crucial for understanding customer behavior and optimizing financial services.

**Top 10 Cities with Highest Transaction Amount**

**Observation:** Austin has the highest average transaction amount followed by Washington, El Paso, and Phoenix.

**Insights:** This graph reveals the top cities with the highest average transaction amounts. This information can be leveraged to identify high-value markets, tailor marketing efforts, and optimize resource allocation. For example, banks can focus on offering enhanced services and targeted promotions in cities with higher transaction volumes.

### CONCLUSION

**Anomaly Detection:** Identifying unusual transaction patterns, such as high-value transactions from specific devices or locations, can help detect and prevent fraudulent activities. Implementing real-time monitoring systems and fraud scoring models based on transaction data can enhance fraud detection capabilities.

**Enhanced Security Measures:** Implementing stronger security measures for high-value transactions, such as multi-factor authentication, can mitigate the risk of unauthorized access and fraudulent activity.

**Optimized Service Channels:** The analysis reveals variations in transaction durations across occupations and channels. This information can be used to optimize service delivery by allocating resources effectively. For instance, dedicated channels or extended service hours can be implemented for occupations with longer transaction durations.

**Proactive Risk Management:** By analyzing transaction data, banks can proactively identify and address potential risks, such as credit risk, operational risk, and reputational risk.

**Compliance:** Analyzing transaction data can help ensure compliance with regulatory requirements and anti-money laundering regulations.

**Personalized Service:** Understanding customer demographics and transaction patterns allows for personalized service offerings. Tailored product recommendations, customized communication, and targeted marketing campaigns can be implemented based on customer needs and preferences.

**Branch Network Optimization:** Analyzing transaction intensity across locations can help optimize the bank's branch network by strategically placing branches in areas with high transaction volumes.

**ATM Placement and Maintenance:** Data on ATM usage patterns can inform the placement and maintenance of ATMs, ensuring optimal accessibility and availability for customers.

**Resource Allocation:** Understanding resource utilization across different channels can help allocate resources effectively, such as staffing levels for branches and call centers.

**Customer Segmentation:** Segmenting customers based on demographics, transaction behavior, and risk profiles allows for targeted marketing campaigns and product offerings.

**Product Development:** Identifying customer needs and preferences based on transaction data can guide the development of new products and services that better meet customer expectations.

