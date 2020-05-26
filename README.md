# Pedestrian Steps Prediction LSTM Model 
#### Pytorch

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

**Paper**: http://cvgl.stanford.edu/papers/CVPR16_Social_LSTM.pdf  

## Documentation
- **generator.py** : Python script for generating artifical datasets
- **helper.py**: Python script includes various helper methods
- **hyperparameter.py**: Pyton script for random best parameter selection for a model
- **make_directories.sh**: Bash script for creation of file structure
- **model.py**: Python file includes Social LSTM model definition
- **olstm_model.py**: Python file includes Occupancy LSTM model definition
- **olstm_train.py**: Python script for training Occupancy LSTM model
- **test.py**: Python script for model testing and getting output txt file for submission
- **train.py**: Python script for training Social LSTM model
- **utils.py**: Python script for handling input train/test/validation data and batching it
- **validation.py**: Python script for externally evaluate a trained model by getting validation error
- **visualize.py**: Python script for visualizing predicted trajectories during train/test/validation sessions
- **vlstm_model.py**: Python file includes Vanilla LSTM model definition
- **vlstm_train**: Python script for training Vanilla LSTM model
