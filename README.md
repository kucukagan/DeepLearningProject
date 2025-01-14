# Folder Structure
## Dataset
This folder contains the Datasets used for training and testing
### train-easy
This folder contains the Datasets used for training and interpolation testing
### train-medium
This folder contains the Datasets used for testing on medium extrapolation tests
### train-hard
This folder contains the Datasets used for testing on hard extrapolation tests
## Models
This folder contains all the code which is able to run. It contains two notebooks, one for each Subproblem mentioned in the paper.
### arithmetic_add_or_sub_images
This folder contains images which were used in the paper to show some examples
### best_arithmetic__add_or_sub_model
This folder contains the checkpoint of the (best) model for the arithmetic__add_or_sub problem used to measure the performance of the model.
### best_calculus_differentiate_model
This folder contains the checkpoint of the (best) model for the calculus_differentiate problem used to measure the performance of the model.
### calculus__differentiate_images
This folder contains images which were used in the paper to show some examples
## Writing
This folder contains the proposal and the paper itself.
# How to Run the Code
* If you have not downloaded the Repository From Github then you have to download the Dataset folder from https://github.com/berniwal/DeepLearningProject/ and replace it as there was not enough space to compress it to a 100MB zip file. Otherwise if downloaded from Github you can skip this step.
* Go to the Models folder and select the Notebook for which subproblem you want to run the code.
* Make sure you have installed the required libraries in the first import statement (tensorflow 2.x) otherwise you will not be able to run the code.
* If you made sure you have installed those libraries, then you should be able to execute the notebook without any further considerations.
# Related Work
## Based on the Paper 'Analysing Mathematical Reasoning Abilities of Neural Models'
https://arxiv.org/pdf/1904.01557.pdf
## Link to Mathematics Dataset
https://github.com/deepmind/mathematics_dataset
## Link to Pre-Generated Dataset
https://console.cloud.google.com/storage/browser/mathematics-dataset?pli=1
## Link to used tutorial about Neural Machine Translation with Attention
https://www.tensorflow.org/tutorials/text/nmt_with_attention
