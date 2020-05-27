# AutoencoderConv
The code of simple convolutional autoencoder to generates deepfake images

# Train circle
Use train-tagged cells to train your model

# Data manipulations
Use Video split cell to split video from pre-specified path into frames.
Then use Face split cell to take faces from frames of previous step. In such a simple way you can collect training data for model.
But don't forget to specify source and destination path.

# Autoencoder architecture
Contained in #Architecture cell! Change it to modify nn's structure.


