# Smart-Equipment-Monitoring-Predictive-Maintenance-Dashboard
Desingend and devloped the Predictive maintanace Smart equipment monitiring system with the data from Kaggle

Conclusion After Analysing the dataset:
This project demonstrated the development of a predictive maintenance solution using machine learning and data visualization techniques to monitor equipment health and identify potential failures. Through data cleaning, exploratory data analysis, feature engineering, and model development, key operational factors influencing machine failures were identified and analyzed.

A Random Forest classifier was trained to predict machine failures using sensor and process parameters such as tool wear, temperature difference, power consumption, torque, and rotational speed. The model achieved high predictive performance, with an overall **accuracy of 99%, precision of 96%, recall of 76%, and an F1-score of 85% for failure detection**.

Feature importance analysis revealed that **Tool Wear, Temperature Difference, Power, and Overstrain Index** were the most significant indicators of machine failure. The analysis also showed that _**Heat Dissipation Failure**_ was the most common failure mode, while low-quality product variants experienced failures more frequently than medium and high-quality variants.

To support decision-making, the processed data and insights were integrated into a Power BI dashboard that provides an interactive view of equipment health, failure patterns, and maintenance risks. This enables maintenance teams to monitor machine performance proactively, reduce unexpected downtime, and support data-driven maintenance planning.

Overall, the project highlights how predictive analytics and business intelligence tools can be combined to improve equipment reliability, optimize maintenance schedules, and enhance operational efficiency in manufacturing environments.

Reference:
S. Matzka, "Explainable Artificial Intelligence for Predictive Maintenance Applications," 2020 Third International Conference on Artificial Intelligence for Industries (AI4I), 2020, pp. 69-74, doi: 10.1109/AI4I49448.2020.00023.
