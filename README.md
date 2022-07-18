# Speech-Recognition-Challenge-Tensorflow-Kaggle

Tensorflow Speech Recognition Challenge was a competiton on Kaggle by Google Brain. 

## Running
The notebooks can be run individually using Jupyter. To run the scripts from command line edit the notebooks using Jupyter and run:

    ./script/execute_notebook.py
   and select the notebook to run. The results are stored in results/notebook_name.log
   

## Architecture
The models that were leveraged for this are:
1. A variant of Convolutional LSTM (https://arxiv.org/pdf/1610.00277.pdf)
2. LSTM-L (https://arxiv.org/pdf/1711.07128.pdf)
3. C-RNN (https://arxiv.org/pdf/1711.07128.pdf)
4. GRU-L (https://arxiv.org/pdf/1711.07128.pdf)
5. Resnet

The final model was a ensemble 13 models. Weighted Averaging and Stacking was used to generate the final predictions.
