# Ball Trajectory Prediction with Kalman Filter and NLopt Optimization

## Project Overview
This project focuses on predicting the trajectory of a moving object, specifically a ball, while accounting for wind effects. The model leverages a Kalman Filter to estimate the ball’s position and velocity, correcting for noise to improve accuracy over time. Additionally, NLopt optimization is used to dynamically adjust model parameters under variable wind conditions, ensuring the model adapts effectively to external forces like wind.

## Features
- **Kalman Filter**: Real-time state estimation of the ball's position and velocity, smoothing noise in measurements.
- **NLopt Optimization**: Optimizes parameters to enhance trajectory prediction accuracy under the influence of wind.
- **Real-Time Updates**: Integrates real-time measurements to refine predictions continuously.

## Requirements
- **Python** 3.x
- **Jupyter Notebook**

### Required Libraries
To set up the environment, install the following Python libraries:
```bash
pip install numpy scipy nlopt matplotlib filterpy
```
## Usage
1. **Setup Environment**: Install the necessary libraries as listed above.
2. **Run the Notebook**: Open and run `ball_tracking.ipynb` in Jupyter Notebook to execute the prediction model.
3. **Adjust Input Parameters**: Customize initial conditions for wind speed and measurement noise within the notebook to simulate different scenarios.

## Project Structure
- **Kalman Filter Implementation**: Predicts the ball's position and velocity, refining estimates as new data comes in.
- **NLopt Optimization**: Adjusts parameters based on real-time feedback to account for wind dynamics.
- **Visualization**: Plots the predicted trajectory alongside actual measurements to demonstrate the model’s accuracy.

## Results
The model demonstrates enhanced accuracy in trajectory prediction under windy conditions. The Kalman Filter smoothens noise in measurements, while NLopt optimization dynamically adjusts to changing wind conditions for robust predictions.

## Future Improvements
- Extend the model to handle varying wind directions.
- Incorporate additional environmental factors affecting trajectory.
