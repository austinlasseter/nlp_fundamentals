https://github.com/udacity/deep-learning-v2-pytorch/tree/master/sentiment-rnn

## Notebook: Sentiment RNN
The next few videos will be all about implementing a complete RNN that can classify the sentiment of movie reviews (positive or negative).

It's suggested that you open the notebook in a new, working tab and continue working on it as you go through the instructional videos in this tab. This way you can toggle between learning new skills and coding/applying new skills.

To open this notebook, you have two options:

Go to the next page in the classroom (recommended).
Clone the repo from Github and open the notebook Sentiment_RNN_Exercise.ipynb in the sentiment-rnn folder. You can either download the repository with git clone https://github.com/udacity/deep-learning-v2-pytorch.git, or download it as an archive file from this link.
Instructions
Load in text data
Pre-process that data, encoding characters as integers
Pad the data such that each review is a standard sequence length
Define an RNN with embedding and hidden LSTM layers that predicts the sentiment of a given review
Train the RNN
See how it performs on test data
This is a self-assessed lab. If you need any help or want to check your answers, feel free to check out the solutions notebook in the same folder, or by clicking here.

GPU Workspaces
The next workspace is GPU-enabled, which means you can select to train on a GPU instance. The recommendation is this:

Load in data, test functions and models (checking parameters and doing a short training loop) while in CPU (non-enabled) mode
When you're ready to extensively train and test your model, enable GPU to quickly train the model!
All models and data they see as input will have to be moved to the GPU device, so take note of the relevant movement code in the model creation and training process.
