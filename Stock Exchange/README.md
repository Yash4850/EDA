# Problem Statement
The file data_sample.csv contains codified features of informational messages that are being produced by a subset of the company servers. Each entry (row) corresponds to a particular informational message that have been received; it contains the UTC timestamp (datetime column) and 3 features (application, node-name and category). Messages themselves are excluded from the dataset. I was asked to produce a high-level summary of any regularly occurring patterns that you may find in this dataset. 
# Insights
- Between 4a.m to 6a.m, the number of applications from Monday to Saturday is at the lowest point of the day.
![alt text](https://github.com/Yash4850/EDA/blob/main/Stock%20Exchange/Figures/1.PNG)

- On Sunday from 1p.m onwards the number of applications are at its lowest point
![alt text](https://github.com/Yash4850/EDA/blob/main/Stock%20Exchange/Figures/2.PNG)

- ‘Application’ is always missing for ‘node’ 6 and category 7
- On Saturday 'Category’ is always missing for 'application' 102 and 'node' 56
- The number of applications, node names and categories are very high at lower values.
