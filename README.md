# Question Answering Task using T5 model.

# Description:

## In this project we are generating Answer of a given Question.


# Project Structure

1. I have taken dataset from kaggle.
2. Data Prprocessing
    - Basically we can call this problem as Text Extraction as well because we will give the contexts along with questions and then our model will generate answers.
    - For Input the tokenization will be done by combining questions and contexts.
    - T5Tokenizer is used for tokenization.  
4. Model Training
    - I have used T5 model in training.
    - T5 model : T5 is an encoder-decoder model pre-trained on a multi-task mixture of unsupervised and supervised tasks and for which each task 
      is converted into a text-to-text format
4. The accuracy of this model can be improved by using some other version of T5.I have trained this model using T5-base model. 

# Libraries
1. PyTorch Lightning
2. Hugging Face 

   

