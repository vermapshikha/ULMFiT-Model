Predicted and classified the user sentiment categories (positive,negative and neutral) on major US Airlines 
with state-of-the-art technique for text classification using supervised ULMFiT model (Transfer Learning).

The pre-processing (tokenization and numericalization) of data for further analysis was done using Language and Classification DataBunch 
Module respectively from fastai package. The model used was pre-trained using WikiText-103 having 103 million words and the twitter data was given to this model. This model was fine-tuned using parameters to get an efficient language model and encoder.

The model then used Classification module for assigning labels to tweets and fine-tuning was done to obtain an efficient decoder. 
Gradual Unfreezing of layers(relu, softmax, AWD-LSTMs) of model was performed which helped in achieving the 
top accuracy of around 83% to predict the user sentiments through tweets

Data Link: https://www.kaggle.com/crowdflower/twitter-airline-sentiment
