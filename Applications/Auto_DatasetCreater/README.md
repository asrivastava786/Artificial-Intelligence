
# Auto Dataset Creater for KYC

In this usecase we want to collect most of information we can get just by sender name.
This information will be useful for us to replying and further product recommendation system.
We will be building and training a basic character-level RNN to classify words.
A character-level RNN reads words as a series of characters - outputting a prediction and “hidden state” at each step, feeding its previous hidden state into each next step. We take the final prediction to be the output, i.e. which class the word belongs to.
* It's just supporting application we use differents other inputs and models as well to get validate outputs. 

## Task: 
Create Dataset from email sender name(customer).

## Input:
Inbox Email Sender Name (String)

## Output:
1) First Name
2) Last Name
3) Gender
4) Language
5) Country 
 

