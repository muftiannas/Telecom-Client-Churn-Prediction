# Telecom-Client-Churn-Prediction

Explanation of Main Tasks
A telecommunications operator named Interconnect wants to forecast their clients' churn rate. 󠀢 󠀳 󠀰 Interconnect's marketing team has collected some personal data from clients, including information about selected data plans and their contracts.

Interconnect Service :
󠀰Interconnect provides two main types of services:

- The landline network.
- The Internet.

Some of the other services that Interconnect provides include:

- Internet security: antivirus software (DeviceProtection) and malicious website blocker (OnlineSecurity)
- Dedicated technical support line (TechSupport)
- cloud storage for file and backup data (OnlineBackup)
- Streaming TV (StreamingTV) and movie directories (StreamingMovies)
- Clients can choose to pay monthly or sign a contract for a 1 or 2 year subscription.

Data Description :
󠀰The available data consists of several files obtained from different sources:

- contract.csv — 󠀰contract information
- personal.csv — 󠀰client personal data
- internet.csv — information about Internet services
- phone.csv — information about phone services
In each file you will find a customerID column with a unique code assigned to each client.

Contract information applies as of February 1, 2020.

In order to achieve the above objectives, we will follow the following steps :

- Import modul and read the data
- Apply Data Preprocession (check duplicate values, missing values, fix data types)
- Apply exploratory data analysis in determining why and what causes customer churn
- Build a machine learning model to forecast Interconnect customer churn

