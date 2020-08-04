## Notebook: Character-Level RNN
Now you have all the information you need to implement an RNN of our own. The next few videos will be all about character-level text prediction with an LSTM!

It's suggested that you open the notebook in a new, working tab and continue working on it as you go through the instructional videos in this tab. This way you can toggle between learning new skills and coding/applying new skills.

To open this notebook, you have two options:

Go to the next page in the classroom (recommended).
Clone the repo from Github and open the notebook Character_Level_RNN_Exercise.ipynb in the recurrent-neural-networks > char-rnn folder. You can either download the repository with git clone https://github.com/udacity/deep-learning-v2-pytorch.git, or download it as an archive file from this link.
Instructions
Load in text data
Pre-process that data, encoding characters as integers and creating one-hot input vectors
Define an RNN that predicts the next character when given an input sequence
Train the RNN and use it to generate new text
This is a self-assessed lab. If you need any help or want to check your answers, feel free to check out the solutions notebook in the same folder, or by clicking here.

GPU Workspaces
The next workspace is GPU-enabled, which means you can select to train on a GPU instance. The recommendation is this:

Load in data, test functions and models (checking parameters and doing a short training loop) while in CPU (non-enabled) mode
When you're ready to extensively train and test your model, enable GPU to quickly train the model!
All models and data they see as input will have to be moved to the GPU device, so take note of the relevant movement code in the model creation and training process.
