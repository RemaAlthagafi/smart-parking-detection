Smart Parking Detection with Pathfinding Optimization 
An advanced computer vision system designed to detect parking occupancy and provide intelligent navigation to the nearest available spot using deep learning and pathfinding algorithms.


Project Overview
This project addresses urban parking challenges by automating the detection of vacant spaces and calculating the most efficient route for the user. By leveraging YOLOv8 and the A* algorithm, the system provides a robust solution for modern smart-city infrastructure.

Objectives
Automated Detection: Identify parking spaces and classify occupancy in complex environments.

High Precision: Ensure reliable detection under varying lighting and shadows without manual pre-processing.

Intelligent Recommendation: Locate the nearest vacant spot based on the user's entry point.

Route Optimization: Compute the shortest path to the recommended space.

System Workflow
Inference: Processing parking lot images through the YOLOv8 Nano model.

Occupancy Mapping: Generating a real-time grid of available vs. occupied slots.

Pathfinding: Applying the A* algorithm to determine the optimal route.

Visualization: Displaying the final recommendation and calculated path.

Core Technologies & Methodology
Architecture: YOLOv8 (Nano) selected for its superior balance between accuracy and resource efficiency.

Pathfinding: A* Algorithm for efficient, cost-based navigation.

Development Environment: Developed and trained using PyTorch.

Dataset
The system was trained and validated on a comprehensive dataset (derived from PKLot). The data covers diverse weather conditions and angles to ensure the model's robustness in real-world scenarios.


Key Learning & Evolution
Initially, traditional methods like HOG and SVM were considered. However, the project evolved to Deep Learning (YOLOv8) to overcome limitations in environmental adaptability and achieve the high precision required for professional deployment.