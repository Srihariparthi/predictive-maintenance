# 🔧 Mitsubishi Smart Predictive Maintenance System

## 📌 Project Description

This project is a machine learning-based predictive maintenance system designed to identify potential machine failures using industrial sensor data. It is inspired by real-world applications in manufacturing environments such as Mitsubishi, where minimizing downtime and improving operational efficiency are critical.

The system uses key parameters such as air temperature, process temperature, rotational speed, torque, and tool wear to predict whether a machine is likely to fail. By analyzing these inputs, the model provides early warnings, enabling proactive maintenance and reducing unexpected breakdowns.

A Random Forest classification algorithm is used to train the model on the AI4I 2020 Predictive Maintenance dataset from Kaggle. The trained model is saved as a serialized file (`model.pkl`) using Python’s pickle module, allowing for fast and efficient predictions without retraining each time.

To make the system interactive and user-friendly, a Streamlit-based web interface is developed. Users can input machine parameters through sliders and instantly receive predictions indicating whether the machine is healthy or at risk of failure.

This project demonstrates the practical application of machine learning in industrial automation and predictive analytics. It highlights skills in data preprocessing, model training, evaluation, and deployment through a simple web interface.

Overall, the system showcases how data-driven approaches can improve reliability, optimize maintenance schedules, and support intelligent decision-making in modern manufacturing industries.
