# Smart-Chatbot
Smart chatbot to automate frequented information.


## Problem.
Waste of time and resources caused by misinformation of employees.
Same/repetitive questions = Similar/repetitive answers.

## Solution

Facilitate the communication  between departments in the company, by the automatization of responses to frequent questions. 

## Future Work
Execute actions/processes.

Using Machine learning/NLP to identify intent of the messages, extract entities and provide an immediate response.

Have special permissions (authorized people who can do certain procedures).

## Chat bot
This chatbot it is able to give immediate responses in 3 possible scenarios:
No matter the sintaxis or the words used it identifies the intention of the message.

1.- Ask something and it gives you the response. e.g. I want to know how to get promoted and it displays the requirements to get the promotion
    1.CV updated 2. the cupervisor will contact each referee ... and so forth.
    
2.- If It identifies that the message is asking for a document (PDF/WORD/EXCEL...) It will send that specific document via email.
    e.g. I want to see my contract... Then It will send you an e-mail with your PDF contract.
    
3.- If the chatbot doesn't identify what we are asking for, It'll ask you for another time, If not It will make a call to the 
     department/person in charge to continue with your inquiry.

This project was made by using AWS, such as:
### Amazon LEX: Chatbot.
### AWS Lambda: Used for the connection between front-back. In cooperation with Amazon Lex to get the intent (key words) of the messages.
### Amazon Connect: Used to make a call to the department/person in charge, if It doesn't recognize the message.
### Amazon SNS: To send Emails once It had identifed that a document is required. 

### Image
![capture5](https://user-images.githubusercontent.com/39096829/41831645-de35e99c-780d-11e8-8bb5-8c0c13a72d89.PNG)
