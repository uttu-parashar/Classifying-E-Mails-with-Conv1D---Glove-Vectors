# Classifying-E-Mails-with-Conv1D---Glove-Vectors


In this project the task was to classify E-mails in 10 given Categories. After cleaning text and all data I Build two Deep Conv1d Neural-Networks. 
  *  in 1st Model after doing tokenization, padding etc.. , I initialized the pretrained Glove Vectors to create an Embedding layer which converts each word in 300-Dim Vectors And passes to next Conv1D Layers of Model. Here i got 75% accuracy is just 5 Epochs of Training.
  * The 2nd Model was same like 1st model. The only diffrence was Here i used charecter level embeddings instead of word level Embeddings of pretrained Glove Vectors.
