# AML-Final-Project
## Predictive Machine Maintenance using Machine Learning 

MIS 382N: Advanced Machine Learning
Prof. Joydeep Ghosh
Fall 2023

#### Group 13:
Kapish Krishna Bodapati |
Mandeep Burdak |
Morgan Tucker |
Zeyu Li

### Introduction:

In today's industrial landscape, where machines and equipment play a pivotal role in the production process, the science of predictive maintenance is nothing short of revolutionary. An industrial process where maintenance only occurs when the machine breaks down will be hugely inefficient, whereas it could be hard for people to think of a maintenance schedule that is predictive enough to the real need for the machine. In our project, we wish to propose a model where we can foresee issues and schedule maintenance before a breakdown occurs.

### Data Source: [Microsoft Azure Predictive Maintenance (kaggle.com)](https://www.kaggle.com/datasets/arnabbiswas1/microsoft-azure-predictive-maintenance/data)

Our dataset is a collection of invaluable telemetry readings. These readings capture the heartbeat of a fleet of 100 machines, providing detailed information about voltage, rotation, pressure, and vibration. Not just numbers on spreadsheets, these readings reveal the health and vitality of our industrial workhorses.

Going deeper into the data, here are five key aspects the data can shed light on:

1. **Errors:** This data tells a story of errors, capturing the moments when these machines faltered. It identifies all types of recordable errors that do not directly - but could potentially, shut down the machines, offering insights into the challenges these machines faced.

2. **Failures:** These are the times when breakdowns occurred, with four different types of failures highlighting the diversity of deadly challenges these machines confront. The severity of failures are much higher than that of errors.

3. **Machine Conditions:** Here, we get to know the physical conditions of machines themselves. We learn about their models and ages, as a primer that could potentially lead us to investigate how the durability of a machine depends on its own setting.

4. **Maintenance Records:** This data shares the types of maintenance these machines received, offering glimpses into their moments of rejuvenation. Their records were set on arbitrary (with industry experience) schedules, but may not necessarily abide by the real maintenance needs.

5. **Telemetry:** It contains 876,100 data points of telemetry readings that describe the general working conditions of the machines.

### Project Focus and Techniques:

1. **Predictive Maintenance for Equipment:** We will primarily focus on data that raises red flags - such as errors and failures, to see when potential maintenance should be performed. We will be using EDAs to discover which factors contribute to maintenance most largely, and employ dimension reduction techniques to avoid overly noisy processes. Our goal is to predict when a machine might falter, using a blend of time series analysis, anomaly detection, and predictive modeling. 

2. **Anomaly Detection in Telemetry Data:** Our machines have a language of their own, and we're building an interpreter to detect when they start to speak differently. We can develop a system that can automatically classify anomalies or deviations from normal operating conditions using the telemetry data. This is crucial for identifying potential issues before they lead to machine breakdown.

3. **Equipment Failure Classification:** We can develop a classification model that can predict the type of failure a machine might experience based on the telemetry data. This will help in understanding the specific issues that different types of machines are prone to and will aid in targeted preventive maintenance.

4. **Comparative Analysis of Predictive Maintenance Algorithms:** We can compare the performance of different predictive maintenance algorithms such as traditional machine learning methods, time series analysis techniques, and deep learning models on this dataset to determine which approach yields the most accurate predictions.

5. **Real-Time Predictive Maintenance System:** We can develop a real-time system that can monitor telemetry data streams and provide alerts or predictions for potential equipment failures. This is a little complicated in my opinion as we have to use real-time streaming data processing frameworks.

### Conclusion:

In closing, this project stands as an endeavor to harness the vast potential of predictive maintenance in industrial operations. By dissecting and analyzing the extensive dataset at our disposal, we aspire to develop pragmatic, data-driven solutions for the challenges that industries face on their machines.
Our objective is straightforward: to make machine maintenance smarter and more reliable, to optimize efficiency, and to bring about cost savings through proactive maintenance. In essence, our work aims to empower organizations to minimize downtime and achieve greater operational resilience through the automate model we propose.
