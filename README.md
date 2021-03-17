# Evaluation Exercise

The code targets data extraction and training and testing of an autoencoder model to minimize the size of dataset along with low information loss.

In the given dataset, we have rows of variable length which contains event-specifiers followed by the kinematic features for each object in the event. The task is to compress the four-momentum of a sample of simulated particles from 4 to 3 variables for jet particles in every event. This task has to be achieved using autoencoders.

Requirements
- Python > v3.0
- PyTorch
- Fastai
- Jupyter Notebook, sklearn

Steps [Refer Jupyter Notebook for complete python codes]:
- Reading the csv dataset
- Processing to extract values against each jet against each event ID
- Normalization
- Creating an autoencoder model
- Training and testing the model with visualization for final model performance against testing dataset

Project contents :
 - Jupyter notebook
 - Presentation file
