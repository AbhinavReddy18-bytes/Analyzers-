# Analyzers- Comparitive Study of legal Analysis using different AI Models

<h1>Datasets</h1>
We have collected datasets for penal codes and we have scrapped the website for the csv files of 2 states in US (California and New York) which we wanted for experimenting.
Then we have manually edited csv files for inconsistent rows and columns and made it as in 3 formats:

1. Uncleaned Dataset
2. Cleaned Dataset 
3. Combined Dataset

Next we have used some general preprocessing techniques like Normalization, tokenizatization, textcleaning and vectorization and many more..

<h1>Working Process: </h1>

Primarily, we have done checking on <b>"BERT Model"</b> for analysis on both datasets with some manually changing the structure of data like removing advertisements, inconsistent data and added a category called "STATE" where combined dataset pops up like which penal code belongs to which state. Had some complications, getting errors, getting memory issues while running this function called <b>torch.no_grad()</b> which is used to train the model with the tokens generated by the "tokenization" pre-processing. We have uploaded the code in this repo for cleaned dataset only because both uncleaned and cleaned datasets are like how many times we do the manual pre-processing, we lost a huge amount of data that many times.

Next, we have implemented the traditional model named <b>"Random Forest Classifer"</b>. 

