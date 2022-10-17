# Analysis-of-Seismic-Signals
Analysis of Seismic Signals using Deep Learning Algorithms for Time Series seismic sensor data. A ***Binary human activity classifier*** that differentiates between walking and running using the ground vibrations.

I proposed a novel method for identifying human activities like walking and running, using ground vibration obtained from seismic sensors and Deep learning algorithms. It is grounded on the idea that each activity generates distinctly unique eismic signatures. The sampling rate of the seismic data recorded is 1000 Hz. The datasets recorded are between 20 to 30 seconds long each. 3 and 4 channel sensors are used to record the dataset. The data is then used to detect peaks by comparing them with neighboring values, and peak-based segmentation is done. The segmented time series are then labelled and used to train Deep Learning models.

Deep learning algorithms such as One-Dimensional Convolutional Neural Networks, 1D CNN and Recurrent Neural Networks [e.g., Long Short-Term Memory (LSTM)] have been used for Human Activity Recognition. Human Activities recorded that would be classified include Walking and Jogging.

The raw 1D time-series seismic sensor data signal:

![1](https://user-images.githubusercontent.com/68142818/196252868-3e7a27a3-5620-4c2f-98dc-6424f65f205f.PNG)

Flowchart of the Methodology proposed:

![3](https://user-images.githubusercontent.com/68142818/196252632-e7f169f0-e29a-4934-9326-bb3356171bde.PNG)

After performing Data Cleaning and Preprocessing, the Deep Learning Algorithm 1D Convolutional Neural Network is used for classification of the activities.

Result as visualized in a Confusion Matrix and the Model Metrics

![2](https://user-images.githubusercontent.com/68142818/196254701-3f0ed959-0815-4c4f-86d4-2a5ab3ba3568.PNG)
![Capture9](https://user-images.githubusercontent.com/68142818/196254930-225057ea-fbf7-4eb4-968b-4d67bde9ebf9.PNG)
