# Lecture Video Summarization
This code was used as my final project for the Applied Deep Learning class (COMS 4995) undertaken at Columbia University during Fall 2020. 
The code is split into 4 parts.
- Preprocessing: 
This was used to convert my repository of class transcripts into a unique structured dataset. I wanted it to be stored in the form of a csv so that it is easily readable and editable. 

- Basic Word Embedding Based Summarization: 
This code was used to build a baseline model that computed document embeddings for each document and picked the 3 sentences that had the highest cosine similarity to the overall document embedding as the summary. The sentence embedding was computed by averaging the word embedding in the sentence and the document embedding was taken as the average of all the sentence embeddings in the document. 

- Extractive Summarization with BERT 
This code used fine-tuned BERT embeddings to attain bi-directional contextual embeddings for al words. I then computed sentence embeddings.
- Abstractive Summarization
