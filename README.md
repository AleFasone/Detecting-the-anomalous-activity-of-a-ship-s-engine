# Detecting-the-anomalous-activity-of-a-ship-s-engine

#Objective
This project focuses on developing a robust Data Science and Machine Learning model to detect anomalous activity in ship engines. The primary goal is to mitigate critical operational and financial risks, ensuring crew safety and optimizing maintenance in the supply chain industry.

Project Objectives
To build a robust anomaly analysis and detection model for ship engines.

To proactively identify potential failures to enable timely and optimized maintenance interventions.

To reduce critical risks such as crew safety hazards, operational disruptions, and significant financial losses.

#Key Variables (Features)
The analysis was performed on a dataset containing six continuously monitored features crucial for evaluating engine status:

Engine RPM (Revolutions Per Minute)

Lubrication Oil Pressure

Fuel Pressure

Coolant Pressure

Lubrication Oil Temperature

Coolant Temperature

#Methodology
The project followed a systematic approach:

Exploratory Data Analysis (EDA):

Conducted thorough statistical and visual EDA to understand data distributions.

Identified missing or duplicate entries and detected preliminary anomalies.

Revealed tendencies towards anomalies, particularly in key engine parameters.

#Anomaly Detection Methods:

IQR (Interquartile Range) Method: Applied for identifying outliers based on statistical thresholds.

One-Class SVM: Utilized this Machine Learning algorithm to construct a separation hyperplane for classifying outliers.

Isolation Forest: Employed this Machine Learning algorithm, which isolates anomalies using random trees, proving highly effective.

#Model Evaluation & Visualization:

Various parameter combinations were tested for the machine learning models to ensure robust and reliable results.

Results were graphically represented using Principal Component Analysis (PCA) for 2D visualization to observe anomaly separation.

#Key Results and Insights
The IQR method proved effective in identifying multivariate outliers, especially when considering multiple simultaneous anomalies, aligning with business requirements.

Both One-Class SVM and Isolation Forest demonstrated strong effectiveness in anomaly identification.

Isolation Forest emerged as a particularly advantageous model due to its non-parametric nature and faster implementation. This makes it a robust and easily adaptable solution, especially beneficial for data where variables do not exhibit normal distributions.

#Conclusion
Implementing this anomaly detection model in production will enable companies to significantly optimize maintenance interventions, leading to:

Fewer breakdowns

Reduced fuel and oil consumption

Increased customer satisfaction due to more punctual deliveries

This project was an excellent opportunity to apply theoretical knowledge to a practical, real-world problem, enhancing skills in data exploration, feature engineering, and the selection of appropriate anomaly detection techniques.
