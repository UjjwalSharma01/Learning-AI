# Overview

## Reinforcement Learning From Human Feedback

is a phenomenon in which you train the AI model or you finetune the AI models to give answers in the way which are most preferable according to the user's needs to give more natural and human and humane responses  
we will be tuning the LLama 2 model in this program

Before finetuning we need data to do so, it requires two datasets namely

- Preference data set
- Prompt Dataset

The datasets here we will be using is the paticular post and it's summary from **REDDIT**, the quality and the way of response of the data sets really depends on the data sets you have taken because there is a lot of human intervention in this task and different people have different preference 

[image 1]



### Why to use?

- It is used when the desired type of output is difficult to explain
- when there is no single correct answer to a specific problem or the way of answering
- it doesn't solve all the problems of toxicity and the other factors of the LLM models but plays a great role in finetuning the LLM model for the special pusposes

## Explaination of Code Lines
- Defining the path
- defining the json to load the file


