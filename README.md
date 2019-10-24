# MNIST-GAN
This is a simple Keras implementation of a generative adversial network that is trained to generate images of numbers similar to images in the MNIST dataset.

## Losses after 100 epochs
![loss function](images/Loss_100_epochs.PNG?raw=true)

## Result after 100 epochs
Randomly generated images after 100 epochs of training.
The generated numbers are clearly recognizable and diverse.
![result](images/numbers_100_epochs.PNG?raw=true)

## Getting Started
You can view the notebook here on github. 
### Run the notebook
#### Prerequisites
- Python 3
- Tensorflow
- Keras
- Jupyter

#### Starting the notebook
Simply open a new terminal in the directory and type:
```bash
> jupyter notebook
```
#### Setup model
make sure you run all codeblocks from top to bottom to setup the network

### Running the tests
To test the model, you only need to run the last codeblock.
This will evaluate the model and print the accuracy for each testset.

## Built With
* [Keras](https://keras.io/) - The framework to create the model
* [Project Jupyter](https://jupyter.org/) - Nice and easy python notebooks