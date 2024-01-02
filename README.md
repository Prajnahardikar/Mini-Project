# Evaluation of Cardiovascular Parameters Using PPG

This project focuses on Photoplethysmography (PPG) for the evaluation of cardiovascular parameters, including heart function, blood vessel elasticity, and blood viscosity. Leveraging the non-invasive nature of PPG, this project aims to design a multifunctional enclosure for the MAX30101 Evaluation kit, enabling data collection from fingertip, wrist, and carotid artery locations. The acquired PPG signals undergo preprocessing, feature extraction, and analysis to derive key cardiovascular parameters.

## Objective
Study and evaluate the High Sensitivity Pulse Oximeter and Heart Rate MAX30101 sensor.
Design a multifunctional enclosure for the MAX30101 Evaluation kit.
Acquire PPG signals from various anatomical locations.
Design an algorithm for feature extraction and further analysis using PPG.

## Project Outline

#### Model Design
Design the sensor and microcontroller enclosure using Fusion 360.
Fabricate the sensor enclosure using 3D Printing with FDM technology.

#### Data Acquisition
Acquire PPG data from finger, wrist, and carotid artery.
Capture PPG signals under different conditions: resting state, pre-exercise, post-exercise.

#### Feature Extraction and Analysis
Preprocess PPG data to remove noise and baseline wandering.
Extract features such as BPM, IBI, SDNN, SDSD, RMSSD, PNN20, PNN50, Low, and High-frequency components.
Utilize a fully automated feature extractor.

## Signal Acquisition from Subjects
The MAX30101 Evaluation Kit is employed to collect PPG signals from subjects in resting positions and during activity. Data is acquired from various anatomical locations, including finger, wrist, and carotid artery.

#### Data Summary

Resting Position:
Male: 75
Diabetic Male: 13
Female: 75
Diabetic Female: 5
Wrist: 10
Carotid Pulse: 10
Bionomadix: 20

Activity (Climbing stairs pre-lunch and post-lunch):
Male: 7
Female: 7
Total Data Collected: 204

## Pre-processing
PPG signals are processed using a high-pass FIR filter and a 16-point moving average filter to remove baseline wandering and noise. The signals are segmented into 5-second windows for ease of analysis.

## Feature Extraction
Features such as BPM, IBI, SDNN, SDSD, RMSSD, pNN50, pNN20, Low, and High-frequency components are extracted using a proposed algorithm. The signals are analyzed for both time and frequency domain parameters.

## Performance Evaluation

#### Analysis and Inference
Understanding the significance of parameters.
Comparing calculated parameters with standard values.
Selecting parameters with strong correlations for further classification talks.
Analyzing ANOVA and t-test results for statistical verification.

#### Statistical Analysis
Boxplots are employed for the standardized display of parameter distributions, helping to identify outliers. Statistical verification of parameters is performed, and adjustments to the algorithm are made to address challenges with peak detection.

## Conclusion
This comprehensive project involves the design of a sensor enclosure, data acquisition from various locations, feature extraction, and statistical analysis of cardiovascular parameters. By leveraging PPG signals, the study aims to contribute valuable insights into cardiovascular health and advance the understanding of physiological responses under different conditions. Ongoing work includes further data analysis and refinement of the algorithm for improved accuracy.
For detailed visualizations and analysis results, refer to the project's report in the respective directory.
