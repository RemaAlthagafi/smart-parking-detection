# Smart Parking Detection with Proximity Recommendations

A computer vision project that aims to detect available parking spaces and recommend the nearest vacant spot based on proximity and path planning.

## Status
**Work in Progress**  
This project is currently under development. The repository includes the project planning and will be updated with implementation, experiments, and final documentation.

## Project Overview
This project focuses on building an intelligent parking assistance system that detects vacant and occupied parking spaces from parking lot images, then recommends the nearest available parking space to the user.

The proposed system combines computer vision techniques with pathfinding algorithms to support smart parking guidance in a practical and scalable way.

## Objectives
- Detect parking spaces from images or video data
- Classify each parking space as **occupied** or **available**
- Recommend the **nearest vacant parking spot**
- Compute the shortest route to the selected parking space
- Provide a clear and efficient parking guidance workflow

## Proposed Workflow
The planned system follows these main stages:
1. Dataset collection and preparation
2. Data cleaning and preprocessing
3. Parking space detection
4. Occupancy classification
5. Nearest parking space selection
6. Shortest-path recommendation
7. Result visualization through a user interface

## Planned Methods
The project proposal includes the following methods and algorithms:
- **HOG** for feature extraction
- **SVM** and **K-NN** for parking space classification
- **A\*** and **Dijkstra** for nearest parking recommendation and shortest path planning

## Dataset
The project is planned to use a pre-processed version of the **PKLot** dataset, which contains parking lot images captured under different weather and lighting conditions.

## Evaluation Metrics
The system is planned to be evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Recommendation Accuracy
- Response Time

## Repository Contents
This repository will be updated gradually to include:
- Project proposal and planning documents
- Source code implementation
- Model training and evaluation
- Experimental results
- Final report and documentation

## Future Work
The next development stages include:
- Implementing the detection and classification pipeline
- Comparing classification performance between models
- Integrating pathfinding for nearest parking recommendation
- Building a simple interface to display results
- Finalizing the complete system and report

## Notes
This project is being developed as part of a university computer vision course and is currently under active progress.