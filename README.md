# Dialog Act Classification with BERT Models

The identification of Dialog Acts (DA) through sequence labeling systems is an important part of Spoken Dialog (SD) understanding. Nowadays DA recognition has gained attention given its importance in Chatbot training, since understanding the role that a user's message plays in a message is crucial in order to respond in an appropriate and helpful way. 

In this work, we perform DA classification adapted to SD, which we implement using 2 BERT models (Bidirectional
Encoder Representations from Transformers): MINI BERT and SMALL BERT. We evaluate the models on the following 3 DA databases from the SILICONE benchmark:

- BT OASIS Corpus
- The Daily Dialog Dataset
- ICSI MRDA Corpus


We compare the models' performances by obtaining their accuracy, their average training time and their loss.
 
We used the SILICONE benchmark that be found in the dataset library from HuggingFace at https://huggingface.co/datasets/silicone
We use BERT through the pytorch implementation provided by the HuggingFace Transformers library. The release is available at https://github.com/google-research/bert

Our repository is organised into two main folders:

- notebooks: This folder contains the notebooks in which we ran each model for the different databases
- img: This folder contains the graphs of the results we obtained from the training of each model for the different databases. There are two types of graphs: ones  that illustrate the Accuracy and others that illustrate the loss of the models for each dataset. 

