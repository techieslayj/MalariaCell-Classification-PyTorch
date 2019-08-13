# MalariaCell-Classification-PyTorch
Predicting parasitized and uninfected malaria cells using Image Classification and Resnet50 model with PyTorch. 

# Instructions 
First download the image dataset from https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria 
I saved it within the local directory where I launched the Jupyter notebook!
** Please launch the jupyter notebook from terminal as follows : jupyter notebook --NotebookApp.iopub_data_rate_limit=1e10

The above ensures that the notebook can handle enough data when running the model and using the resnet50 dataset

# Results
I obtained 84% accuracy when running my model in detecting correctly whether a cell image was parasitized (contains malaria) or uninfected (no malaria present). Using MacBook Pro 2018 the model takes about 3-4 hours to run for 4 epochs. Running the alogorithm for more epochs most likely would have increased my accuracy I obtained however I did not test this due to computer limitations.

THANK YOU!
