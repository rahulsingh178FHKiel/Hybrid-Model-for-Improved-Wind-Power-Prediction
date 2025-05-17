# Literature Review

Approaches or solutions that have been tried before on similar projects.

**Summary of Each Work**:

- **Source 1**: Performance Improvement of Artificial Neural Network Model in Short-term Forecasting of Wind Farm Power Output

  - **[Link](https://ieeexplore.ieee.org/document/9082068)**
  - **Objective**: To enhance the accuracy and stability of short-term wind power forecasting Artificial Neural Networks by using new techniques.
  - **Methods**: The study improves existing ANN models by varying  the number of prior time periods used as input features to refine short-term predictions and incorporating meteorological data  an additional reference wind farm station.
  - **Outcomes**: Both of the optimization  resulted in individual and combined improvements, with the accuracy increasing as the Mean Absolute Relative Error (MARE) reduced by up to 7.5%  and enhanced stability over longer horizons, reducing error fluctuations in wind power predictions.
  - **Relation to the Project**: This paper directly supports the Hybrid Model for Improved Wind Power Prediction by providing insights into ANN-based forecasting enhancements. The findings can be integrated into the project by using multi-source meteorological data to refine input features and optimizing ANN architectures for better short-term forecasting.

- **Source 2**: Short-term wind power forecasting using evolutionary algorithms for the automated specification of artificial intelligence models

  - **[Link](https://www.sciencedirect.com/science/article/abs/pii/S016920700800099X)**
  - **Objective**:To introduce a new short-term prediction method that uses evolutionary optimization algorithms (Particle Swarm Optimization and Differential Evolution) for the automated specification of Artificial Intelligence models, specifically Neural Networks and Nearest Neighbour Search, for wind power forecasting.
  - **Methods**:The study employs evolutionary algorithms (Particle Swarm Optimization and Differential Evolution) to automatically select input variables and internal model parameters for Neural Network (ANN) and Nearest Neighbour Search (NNS) prediction models.  The method uses predicted weather data and historical power data from the target wind farm, as well as historical power data from other distant wind farms, as inputs.
  - **Outcomes**: The application of these optimization algorithms resulted in a reduction of the prediction error when compared to Neural Network models with standard manually selected variables.  The best results showed a mean improvement in prediction error of 9.6% compared to persistence when using an ANN automatically specified by Particle Swarm Optimization.  A further reduction in error (mean improvement of 10.75% over persistence) could be achieved by averaging the model output of the automatically specified Neural Network and the Nearest Neighbour search-based prediction approach. 
  - **Relation to the Project**: This paper is relevant as it explores the use of evolutionary algorithms for optimizing AI models in wind power forecasting, which aligns with the project's aim of developing a Hybrid Model for Improved Wind Power Prediction. The findings on automated variable selection and model specification can inform the development of the hybrid model by suggesting methods to enhance model performance and reduce manual tuning efforts. The use of data from multiple wind farm locations also presents an interesting approach for potentially improving the project's model.

- **Source 3**: New Hybrid Deep Neural Architectural Search-Based Ensemble Reinforcement Learning Strategy for Wind Power Forecasting

  - **[Link](https://ieeexplore.ieee.org/document/9609674)**
  - **Objective**: To propose a novel hybrid ensemble reinforcement learning (ERL) framework for wind power forecasting. It integrates deep neural architecture search and ensemble strategies to improve prediction accuracy and model robustness.
  - **Methods**: Ensemble Reinforcement Learning (ERL): Trains multiple agents (models) in parallel, combining their outputs to reduce overfitting and improve prediction stability. Neural Architecture Search (NAS): An automated method to find the best deep learning model structure (layers, neurons, etc.) for the specific task.
  - **Outcomes**: The hybrid ERL method outperformed all baseline models on real-world wind datasets. It achieved lower RMSE and MAE values, indicating better forecasting accuracy. The proposed approach showed better generalization and adaptability to noisy, non-stationary wind power data.
  - **Relation to the Project**: This paper is highly relevant to your topic as it presents a hybrid model combining deep learning, feature selection, architecture search, and ensemble reinforcement learning to improve wind power prediction accuracy. It provides a strong benchmark and methodological inspiration for our literature review.
