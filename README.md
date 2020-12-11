![FS_GZ](/Assets/FS_GZ.jpeg)

# ML Project: Hotel Cancellation Prediction

UPenn CIS520 Machine Learning class project: utilize different machine learning approaches to predict the hotel booking's cancellation. 

**Authors**: Yifei Li, Zhijian Yang

## Links

* [PDF: Project Report](/CIS520_Project_Report.pdf)
* [Notebooks: Dataset Cleaning and Visualization](/Data_Cleaning_and_Visualization.ipynb)
* [Notebooks: Basic Models Experiment](/Basic_Models_Experiment.ipynb)
* [Notebooks: Advanced Models Exploration](/Advanced_Models_Exploration.ipynb)
* [Dataset: Raw](/Dataset/hotel_bookings.csv) [1]
* [Dataset: Processed](/Dataset/hotel_bookings_processed.csv)

## Problem Formulation

Binary classification:

*   Predict: `IsCancelled` or not:  y={0,1} with dim=2
*   Observations: processed feature set: X with dim=194

## Models

*   Deep Factorization-Machine (half-done)
*   Soft-Voting Ensemble Estimator
*   Neural Network (vanilla and tuned)
*   Random Forest (vanilla and tuned)
*   Decision Tree
*   XGBoost
*   AdaBoost
*   Extra Trees
*   SVM (vanilla and tuned)
*   Logistic Regression (baseline)

## References

[1] Nuno Antonio,  Ana de Almeida, and Luis Nunes. Hotelbooking demand datasets. *Data in Brief*, 22:41 – 49, 2019.

## Credits

* Source of the background picture: Four Seasons Hotel in Guangzhou

