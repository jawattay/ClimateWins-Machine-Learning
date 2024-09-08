# Using Machine Learning to Understand & Predict Weather Patterns in Europe

## Project Overview
This project leverages machine learning models to assess historical weather data and predict future climate scenarios in Europe. The aim is to identify patterns, detect anomalies, and determine the safest regions to live in over the next 25-50 years. The project was presented to stakeholders on **September 8, 2024**, as part of ClimateWins' initiative to enhance infrastructure and disaster preparedness using data-driven insights.

## Objectives
The primary goals of this project are:
- **Finding new patterns** in weather changes over the past 60 years.
- **Identifying weather patterns** outside the regional norm in Europe.
- **Determining if unusual weather patterns** are increasing over time.
- **Generating future weather scenarios** for the next 25-50 years.
- **Identifying the safest regions** in Europe for habitation over the next 25-50 years.

## Thought Experiments
The project focused on three key thought experiments:

1. **Generating Future Weather Scenarios**  
   - Models used: **Random Forests**, **Generative Adversarial Networks (GANs)**
   - Goal: Simulate future weather conditions based on 100 years of historical data across 18 European weather stations.
   - **Outcome:** Highest accuracy achieved with optimized Random Forest, providing 100% accuracy in predicting weather conditions at Budapest weather station.
  
2. **Determining Whether Unusual Weather Patterns are Increasing**  
   - Models used: **Convolutional Neural Networks (CNNs)**, **Random Forests**
   - Goal: Analyze time-series data to track changes in the frequency and intensity of unusual weather patterns over time.
   - **Outcome:** The CNN model achieved 82% accuracy in classifying weather images, but further improvements are needed to enhance real-time monitoring.

3. **Identifying Safe Regions in Europe**  
   - Models used: **Random Forests**, **k-Nearest Neighbors (kNN)**, **Hierarchical Clustering**
   - Goal: Identify regions that will remain safe based on projected weather conditions over the next 25-50 years.
   - **Outcome:** Safe regions were identified through clustering, with further refinement using kNN to compare regions with similar profiles.

## Machine Learning Models
The following models were used throughout the project:
- **Random Forests**: Used for feature importance analysis and predictive accuracy in weather classification.
- **Convolutional Neural Networks (CNNs)**: Applied for spatial pattern recognition in weather images.
- **Recurrent Neural Networks (RNNs)**: Leveraged for trend analysis over time using historical weather data.
- **Generative Adversarial Networks (GANs)**: Simulated future weather scenarios to predict potential climate changes.
- **k-Nearest Neighbors (kNN)**: Classified regions based on their similarity to known safe or risky areas.

## Ethical Considerations
Ethical principles are key to the responsible use of machine learning in this project. The following issues were prioritized:
- **Fairness & Bias Mitigation**: Ensuring the models do not disproportionately categorize regions or populations unfairly due to unbalanced data.
- **Transparency**: Clearly communicating how models make predictions and ensuring stakeholders understand the underlying processes.
- **Data Privacy**: Protecting sensitive data, such as population and socioeconomic information, by adhering to GDPR and other regulations.
- **Social Responsibility**: Ensuring that model outputs are used responsibly, especially when influencing policy and infrastructure planning.

For more details, see the [Ethical Considerations](#) section of the presentation.

## Recommendations
Based on the success of the experiments, the following recommendations were made:
1. **Expand Data Collection**: Incorporate additional weather stations, socioeconomic data, and real-time satellite imagery for more robust predictions.
2. **Model Optimization**: Continue refining the Random Forest and GAN models to enhance predictive accuracy and simulate a broader range of future scenarios.
3. **Pilot Study**: Conduct regional pilot studies in areas identified as climate-vulnerable to validate the model's predictions in real-world scenarios.
4. **Collaboration**: Work closely with local governments and climate experts to ensure that model outcomes align with existing climate resilience plans.

## Presentation
You can access the full presentation in the files provided in this repository.

## Contact
**Presenter:** Josh Wattay  
**Email:** [jawattay@gmail.com](mailto:jawattay@gmail.com)

For any questions or further information, please feel free to reach out.
