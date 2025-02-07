# Banking-Chatbot
Developed a banking chatbot which can guide a person with any banking queries. 

## ChatBot with interactive UI using simple web socket server 
### Description of files
* Chatbot_train.py file trains the data available in the data folder. Once it is trained , the result will be stored as db.sqlite.
* Chatbot.py uses this db.sqlite to generate responses for user queries.
* server.py sends back message to the client.

### How to run
* Once you downloaded this project , Make sure you install the python packages mentioned in requirement.txt.
* Go to Chatbot_Project directory and run python server.py.
* Above step will open the server. Now right click the index.html page and open with brower. You will be able to see the chat window where you can start the conversation and test.


## 🚀 Features  
✅ **Machine Learning & NLP** – Uses Scikit-learn and NLP techniques to process user queries.  
✅ **Custom Dataset** – Trained on a **1,700+ banking queries dataset** for accurate responses.  
✅ **SQL Integration** – Efficient data handling and retrieval for better performance.  
✅ **Front-end UI** – Simple **HTML-based interface** for user interaction.  
✅ **Automated Query Resolution** – Reduces response time and improves customer experience.  

## 🛠️ Tech Stack  
- **Python** (Flask for back-end)  
- **NLP & ML** (Scikit-learn, NLTK, SpaCy)  
- **SQL** (for storing and retrieving query responses)  
- **HTML/CSS** (for the chatbot interface)  
