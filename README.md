# Pedestrian Steps Prediction LSTM Model

Pedestrians follow different trajectories to avoid obstacles
and accommodate fellow pedestrians. Any autonomous
vehicle navigating such a scene should be able to foresee
the future positions of pedestrians and accordingly adjust
its path to avoid collisions. This problem of trajectory prediction
can be viewed as a sequence generation task, where
we are interested in predicting the future trajectory of people
based on their past positions. Following the recent success
of Recurrent Neural Network (RNN) models for sequence
prediction tasks, we propose an LSTM model which
can learn general human movement and predict their future
trajectories.
