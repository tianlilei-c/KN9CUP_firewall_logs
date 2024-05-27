### Firewall Logs Repository

This repository contains firewall log data structured for use in machine learning models such as K-Nearest Neighbors (KNN) or Support Vector Machines (SVM). The repository is categorized into three datasets based on the size of the data:

1. **Large Dataset**: Contains approximately 15,000 log entries.
2. **Normal Dataset**: Contains approximately 3,000 log entries.
3. **Small Dataset**: Contains approximately 500 log entries.

Each log entry in the datasets is structured with the following columns:

1. **Column 1 & 2**: The date and time when the log entry was recorded.
2. **Column 3**: The source IP address from where the traffic originated.
3. **Column 4**: The destination IP address to where the traffic is headed.
4. **Column 5**: The firewall rule that was applied to the traffic.
5. **Column 6**: The source port number from where the traffic originated.
6. **Column 7**: The destination port number to where the traffic is headed.
7. **Column 8 & 9**: The severity level of the log entry (e.g., INFO, WARN, ERROR).
8. **Column 10 & 11**: The brief message or content describing the log entry.
9. **Column 12**: The type of protocol used in the traffic (e.g., TCP, UDP).
10. **Column 13**: The service associated with the traffic.
11. **Column 14**: The status flag indicating the state of the connection.
12. **Column 15**: The number of bytes sent from the source.
13. **Column 16**: The number of bytes sent to the destination.
14. **Column 17**: The duration of the connection or session.

This format ensures that the data is ready for preprocessing and feature extraction, making it suitable for training and testing machine learning models.