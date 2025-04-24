# Explained-RNN
RNN network that finds the place of the defect in time series

In this project I will create a RNN model that determines if a given example has a given defect.

Each example is a combination of 3 sine waves with some noise. Each of the 5 defects possible in data is introduced in createRow function. The defects can exist together.

After the model is trained an effort to explain it was made:
 - There is a method that points to the channel where the defect is coming from (we assume this has to be checked per example and that a defect is not assigned to a specific channel)
 - Another method shows where the defect has occured in time