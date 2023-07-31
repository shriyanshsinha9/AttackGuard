# AttackGuard
AttackGuard is an API-based detection of DDoS Attacks Using ML Techniques &amp; Deep Learning Algorithms
# Stages
The experimental setup for detecting DDoS attacks using deep learning algorithms typically involves the following stages:<br>
1) Data collection: Network traffic data is collected from the server(s) that are being monitored for DDoS attacks. Wireshark is used to capture the data and export it to a CSV file. Low Orbit Ion Canon tool is used to generate attacks on target IP's and machines. <br>
2) Data pre-processing: The collected data is pre-processed to remove any noise, irrelevant information, or duplicates. This step also involves feature selection and extraction, where essential features are selected for training the deep learning models.<br>
3) Data splitting: The pre-processed data is split into training, validation, and test sets. The training set is used to train the deep learning models, the validation set is used to tune hyperparameters and prevent overfitting, and the test set is used to evaluate the performance of the trained models.<br>
4) Model training: Various deep learning models, such as ANN, RNN, LSTM, GRU, etc., are trained using the training data. The hyperparameters of the models are tuned using the validation set to optimize the performance of the models.<br>
5) Model evaluation: The trained models are evaluated using the test set to measure their performance in detecting DDoS attacks. Various performance metrics, such as accuracy, precision, recall, F1 score, ROC-AUC, etc., are used to evaluate the models.<br>
6) Comparison: The performance of different deep learning models is compared to select the best-performing model(s) for detecting DDoS attacks.<br>
7) Deployment: The selected deep learning model(s) are deployed and integrated with Flask API hosted using ngrok to detect DDoS attacks in real-time.

# High-Level Diagrams
![Screenshot 2023-07-31 185422](https://github.com/shriyanshsinha9/AttackGuard/assets/126511293/bbfb6e2f-f85c-4bbe-b76a-c831990ee79a)
<br>

![Screenshot 2023-07-31 185453](https://github.com/shriyanshsinha9/AttackGuard/assets/126511293/c388816e-9767-4638-83e0-2d5763684973)
<br>
![Screenshot 2023-07-31 185513](https://github.com/shriyanshsinha9/AttackGuard/assets/126511293/b09044b6-114b-420b-9945-e69b28373c9c)
<br>
# Output
![Screenshot 2023-07-31 174614](https://github.com/shriyanshsinha9/AttackGuard/assets/126511293/1f7e00b3-a2be-4b73-a1ce-5810b387424d)
