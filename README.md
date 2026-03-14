# Military Load Carriage Injury Prediction via Wearable Sensors

Description:
This repository contains the dataset and algorithmic framework for predicting musculoskeletal limb injuries in elite military personnel. Traditional models rely on static weight and distance metrics, which fail to capture the kinetic reality of the battlefield. To address this, we engineered a custom biomechanical physics engine that integrates simulated tactical load profiles with dynamic triaxial accelerometer data.

By modeling extreme "tabbing" paces and removing doctrinal weight caps (the 40kg limit), this framework captures the multiplicative injury risk of carrying heavy loads over unstable terrain. The repository includes the synthetic hybrid dataset, the physics-based risk generator, and a comprehensive suite of machine learning classifiers evaluated to find the optimal deployment model for tactical injury prediction.

Key Features:

📊 Hybrid Dataset: 3,000 elite infantry profiles merged with real-world human activity recognition (HAR) triaxial sensor data.

🧮 Biomechanical Physics Engine: A custom mathematical model calculating the compounding risk of Load $\times$ Vibration.

🏃 Kinematic Feature Extraction: Utilization of X, Y, and Z-axis acceleration variance to decode complex gait instability and joint impact.

🤖 Predictive Modeling: Comprehensive benchmarking of advanced ML classifiers, including CatBoost, AdaBoost, Gradient Boosting, Random Forest, Decision Trees, Support Vector Machines (SVM), K-Nearest Neighbors (KNN), and Multilayer Perceptron (MLP) neural networks.