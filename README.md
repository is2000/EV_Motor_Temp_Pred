# EV Motor Temperature Prediction

### Technologies

* Julia

* Feed Forward Neural Network (FFNN)

* Data Science

This project predicts the temperature of an electric vehicle (EV) motor using deep learning techniques. The goal is to provide accurate temperature forecasts for better thermal management and efficiency in EV systems.

### Project Overview

* Developed a FFNN model with Autoregressive Rollout to predict motor temperatures from time-series sensor data.

* Preprocessed and structured dynamic motor data to improve model performance.

* Trained and evaluated the model using Mean Squared Error (MSE) metrics.

* Implemented in Julia, leveraging its speed and dynamic system modeling capabilities.

### Features

* Handles time-series data from motor sensors.

* Captures dynamic motor behavior under varying operational conditions.

* Provides predictive insights to improve thermal management in EVs.

### Installation

1.  **Clone the repository:**

    ```bash
    git clone [https://github.com/yourusername/ev-motor-temp-prediction.git](https://github.com/yourusername/ev-motor-temp-prediction.git)
    cd ev-motor-temp-prediction
    ```

2.  **Install Julia and Jupyter:**
    Follow the official instructions to install Julia and set up a Jupyter environment to run Julia notebooks.

3.  **Install required Julia packages:**
    Open a Julia terminal or a new notebook cell and run the following commands:

    ```julia
    using Pkg
    Pkg.add(["IJulia", "Flux", "CSV", "DataFrames", "Plots"])
    ```

### Usage

1.  Open the `final_task_colab3.ipynb` notebook in your Jupyter environment.

2.  Run the cells sequentially to see the model training, evaluation, and results.

3.  Modify the code or data as needed within the notebook to experiment with the model.

### Results

* Provides temperature predictions for EV motors.

* Evaluates model performance using MSE.

* Plots predicted vs. actual temperature trajectories.

icense.
