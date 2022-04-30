# Cyber-Security-Network-Security-Network-Intrusions-Detection-Case-Study
Business Objective:
With the enormous growth of computer networks usage and the huge increase in the number of
applications running on top of it, network security is becoming increasingly more important. All the
computer systems suffer from security vulnerabilities which are both technically difficult and
economically costly to be solved by the manufacturers. Therefore, the role of Intrusion Detection
Systems (IDSs), as special-purpose devices to detect anomalies and attacks in the network, is
becoming more important.

The research in the intrusion detection field has been mostly focused on anomaly-based and misusebased
detection techniques for a long time. While misuse-based detection is generally favoured in
commercial products due to its predictability and high accuracy, in academic research anomaly
detection is typically conceived as a more powerful method due to its theoretical potential for
addressing novel attacks.

As part of this project, your task is to build network intrusion detection system to detect anomalies
and attacks in the network.

There are two problems:
Binomial classification: Detect anomalies by predicting Activity is normal or attack
Multinomial Classification: Detecting type of activity by predicting Activity is Normal or Back or
Buffer Over flow or FTP Write or Guess Password or Neptune or N-Map or Port Sweep or Root Kit or
Satan or Smurf

Hints about Data: Different attack data set have different number of observations. This data is an
example of imbalance data.

Data Preparation:
You are required to append all the files and create new column called attack based on the name of
attack. While you are appending the files, you can take resampling of data based on the number of
attacks.
For Binomial classification, you can create attack variable with attack vs. normal
For Multinomial classification, you can create attack variable with normal vs. Back vs. Buffer Over
flow vs. FTP Write vs. Guess Password vs. Neptune vs. N-Map vs. Port Sweep vs. Root Kit vs.
Satan vs. Smurf

Pl download the following files:
1. Code file in .ipynb formats for Bionomial and multinomial classifications
2. Data files in Data folder
3. correlations, numerical and categorical summaries files as .csv format
4. Output as .xlsx format
5. model save as pickle object
6. 
