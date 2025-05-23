# Literature Review

Approaches or solutions that have been tried before on similar projects.

**Summary of Each Work**:

- **Source 1**: Performance Improvement of Artificial Neural Network Model in Short-term Forecasting of Wind Farm Power Output

  - **[Link](https://ieeexplore.ieee.org/document/9082068)**
  - **Objective**: To enhance the accuracy and stability of short-term wind power forecasting Artificial Neural Networks by using new techniques.
  - **Methods**: The study improves existing ANN models by varying  the number of prior time periods used as input features to refine short-term predictions and incorporating meteorological data  an additional reference wind farm station.
  - **Outcomes**: Both of the optimization  resulted in individual and combined improvements, with the accuracy increasing as the Mean Absolute Relative Error (MARE) reduced by up to 7.5%  and enhanced stability over longer horizons, reducing error fluctuations in wind power predictions.
 
   ![image](https://github.com/user-attachments/assets/a7dee63f-1596-4f07-bf20-2e2f2c42f3c8)

  - **Relation to the Project**: This paper directly supports the Hybrid Model for Improved Wind Power Prediction by providing insights into ANN-based forecasting enhancements. The findings can be integrated into the project by using multi-source meteorological data to refine input features and optimizing ANN architectures for better short-term forecasting.

- **Source 2**: Short-term wind power forecasting using evolutionary algorithms for the automated specification of artificial intelligence models

  - **[Link](https://www.sciencedirect.com/science/article/abs/pii/S016920700800099X)**
  - **Objective**: Use evolutionary algorithms to automate the design of AI models (ANN and Nearest Neighbour Search) for wind forecasting.
  - **Methods**: Applied Particle Swarm Optimization (PSO) and Differential Evolution (DE) to select inputs and tune model parameters, using weather and power data from both local and remote wind farms.
  - **Outcomes**: Models optimized with PSO outperformed manually tuned ones, reducing prediction error by up to 10.75% over baseline.
    - ![image](https://github.com/user-attachments/assets/fd31dce1-1b83-4abe-a863-69c7b91ee29a)
  - **Relation to the Project**: Supports our project’s use of automation and optimization for model tuning. Also reinforces the benefit of incorporating data from multiple wind farms.

- **Source 3**: New Hybrid Deep Neural Architectural Search-Based Ensemble Reinforcement Learning Strategy for Wind Power Forecasting

  - **[Link](https://ieeexplore.ieee.org/document/9609674)**
  - **Objective**: To propose a novel hybrid ensemble reinforcement learning (ERL) framework for wind power forecasting. It combines deep neural architecture search and ensemble strategies to improve prediction accuracy and model robustness.
  - **Methods**: Ensemble Reinforcement Learning (ERL): Trains multiple agents (models) in parallel, combining their outputs to reduce overfitting and improve prediction stability. Neural Architecture Search (NAS): An automated method to find the best deep learning model structure (layers, neurons, etc.) for the specific task.
  - **Outcomes**: The hybrid ERL method outperformed all baseline models on real-world wind datasets. It achieved lower RMSE and MAE values, indicating better forecasting accuracy. The proposed approach showed better generalization and adaptability to noisy, non-stationary wind power data.
  - ![image](https://github.com/user-attachments/assets/a296f4b3-6beb-472c-94ca-46be0e72535c)
  - **Relation to the Project**: It presents a hybrid model combining deep learning, feature selection, architecture search, and ensemble reinforcement learning to improve wind power prediction accuracy. It provides a strong benchmark and a good methodological reference for our literature review.
