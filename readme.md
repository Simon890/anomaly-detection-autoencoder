# Heart cycle anomaly detector with autoencoder

This repository presents a project focused on **cardiac anomaly detection** using **autoencoders**, a deep learning approach tailored for identifying anomalies in unbalanced datasets. The motivation behind this project stems from the critical importance of early and accurate detection of cardiac anomalies to improve patient outcomes and advance diagnostic technology.

## Why autoencoders?
In the context of unbalanced datasets, where normal cardiac events significantly outnumber anomalies, traditional classification models usually struggle due to insufficient representation of minority classes. Autoencoders, however, excel in such scenarios by learning to reconstruct normal patterns. Anomalies, being inherently different from normal patterns, result in higher reconstruction errors, making them detectable.