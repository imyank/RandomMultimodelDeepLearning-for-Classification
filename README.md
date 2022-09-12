This project is the implementation of paper: https://arxiv.org/abs/1805.01890

In this project ensemble model of CNN, LSTM, DNN has been used to provide correct architecture to be used depending on the input. 
This project is useful in such cases when the input is a combination of Text or images based on it the model identifies 
which architecture will work well.

## Dataset used:

Authors have run the model for 500 epochs with 3,9,15 combinations of each
DNN, LSTM-GRU, and CNN but it will take many days to run for
this number of epochs. To produce the results we have used 10
epochs for MNIST and 5 for the IMDB dataset with a
combination of two from each of the architectures

1- **IMDB(https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews):

The model was trained and evaluated on the IMDB dataset. Five epochs run for a single combination. For two
combinations ten epochs and for three architecture total of thirty epochs will be there. The RMDL accuracy achieved
for the ensemble model was around 87.26%.

2- **MNIST(https://www.tensorflow.org/datasets/catalog/mnist):
The RMDL model gives a result on each DNN, LSTM-GRU, and CNN among all three best performances
from the CNN model. The other two did not perform well as in image classification, the importance of long term or short
term memory is less and moreover, RMDL selects the optimizer as per the input. 



## For detail implementation refer the report
