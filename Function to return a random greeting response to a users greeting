text = corpus
sentence_list = nltk.sent_tokenize(text)
print(sentence_list)
def greeting_response(text):
  #Convert the text to be all lowercase
  text = text.lower()
  # Keyword Matching
  #Greeting responses back to the user from the bot
  bot_greetings = ["hello","hi", "hey", "what's good",  "hello","hey there"]
  #Greeting input from the user
  user_greetings = ["hi", "hello",  "hola", "greetings",  "wassup","hey"] 
  
  #If user's input is a greeting, return a randomly chosen greeting response
  for word in text.split():
    if word in user_greetings:
      return random.choice(bot_greetings)
      
def index_sort(list_var):
  length = len(list_var)
  list_index = list(range(0, length))

  x  = list_var
  for i in range(length):
    for j in range(length):
      if x[list_index[i]] > x[list_index[j]]:
        temp = list_index[i]
        list_index[i] = list_index[j]
        list_index[j] = temp
  return list_index
  
