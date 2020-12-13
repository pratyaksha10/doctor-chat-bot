# doctor-chat-bot
chat bot  which helps you in your disease doubts
We need to install a few packages nltk and newspaper3k . NLTK is the Natural Language Tool Kit package, which is a popular package for NLP with Python. Newspaper3k is a python package used for extracting and parsing newspaper articles.

Import The Libraries & Packages
Next import the libraries. We will use the newspaperlibrary to extract the text from the website by using the Article class. We will use the random library to generate a random number for our greeting response. We will use the string library to process the standard Python string. Thesklearn.feature_extraction.text library will be used to get the count vectorizer class countVectorizer to vectorize the text and evaluate how important a word is to a document. From the sklearn.metrics.pairwise library we will get the cosine_similarity method to see how similar the text is to the users queries. We will also import the numpy library to use some of it’s methods like the sort() method. Last but not least we will use the warnings library to ignore the warnings we get with this program.

Tokenize The Data
Next, we will tokenize the text by getting a list of sentences from the text.

Next we will use keyword matching (a rule based approach) to check for greeting type words as input from the user and respond back with a randomized greeting as output.
To do this we need to create a list of greeting inputs (the greetings we expect from the user) and then we will create a list of greeting responses (the greetings that our chat bot will use).
Then we will create a function to check for the users greetings and randomly choose a greeting response back.

Create a function to return the indices of the values from an array in sorted order by the arrays values. This function will help return the chat bot response.

Generating The Chat Bot Response
We are going to create a function which will take in a users response or queries, and then send back the best response(s) selected from the corpus.

Start The Conversation
We can now create a continuous loop for the chat bot to converse with the user. We will run this loop until the users response is ‘exit’.
