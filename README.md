# Keyword-Extraction-with-BERT
Motivation:
It started when I was wondering about how a machine perceives a sentence and take in semantics as compared to humans. Then, I came to know about Bidirectional Encoder Representations from Transformers (BERT), which is a Machine Learning (ML) model for Natural Language Processing (NLP) that is developed by Google, which helps in keyword extraction with its pre-trained models.

Tools/technologies/methodologies:
First, we import necessary libraries. Then, we create a pretrained BERT model using the token classification model class. Then we create a Tokenizer by using the auto tokenizer class. The tokenizer is used to tokenize the strings. 
We must create a Reddit app instance and can access Reddit using our credentials. We then choose any subreddit of our choice and we consider the top post of the month for further processing. We then extract all the comment list of the post. 
Data is pre-processed before being fed into NN. We then must perform standard tokenization. We then create the tokenized input. The data is fed into Neural Network for classification. Then, we categorize the words into one of the 9 pre-defined classes of NER tags. Thus, the keyword extraction is done successfully. 
Then, we display the keywords with their corresponding category. Then, we perform various analysis on it and use data visualization to understand it better. We display keyword with their respective no. of occurrences. The data visualization is done using bar graph, word cloud and pie chart. 

Skills gained (technical and otherwise):
This project helped me in knowing and implementing BERT. It gave me an idea as to how pretrained models work. It was great to see how accurate the pretrained BERT models are. Apart from that, I learnt various techniques like Tokenization, implementing various kinds of data plots like word cloud, pie chart etc.

Impact/obstacles:
The main obstacle that I faced during this project is the lack of information about BERT on the internet, as it was a recent development during the time I started working on this project. I had to do a lot of research to know more about it and to finally be able to implement it. It helped me in creating better models by understanding the working methodology of BERT. 
