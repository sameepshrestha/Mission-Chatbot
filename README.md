# Mission-Chatbot -More information on the individial notebook
Trying to create a chatbot for facebook messenger. Chatbots are mostly locally biased and are suitable for the reason they are trained. This would be my own chatbot for replying the messages in my facebook though the data is not as clean as any standard data source. From what I've read so far in multiple research papers is that the complexity or stacking of the LSTM rarely helps improve the model though it will depend upon the case itself.  Attention based LSTM are said to be mora accurate than the normal LSTM as well as stacked LSTM. So we intend to go first with normal LSTM and  compare its performance with attention model. We would be using Word2vec model to train create our own word vectors as words like 'k gardai xas ' would rarely be present in any standard data source. The most intensive task in this approcah are the data preprocessing and tuning of parameters.

total data for learning after cleaning is 36k 
total uniquw words in the vocab is 38k 

Implementing word2vec 
Word2vec is a relatively simple method of obtaining the vectors for representing the data 
Tomas Mikolov discussed about its implementation in the paper https://arxiv.org/pdf/1310.4546.pdf
Both CBOW and skip-gram implementation is possible in this the implemetation was carried out with the help of the code available in the https://www.tensorflow.org/tutorials/text/word2vec though i dont think its a relatively tough topic to look into but its ok if you understand everything isn't it. Well  i hope so 

LSTM model 
Lets move towards training the actual model then 

 
