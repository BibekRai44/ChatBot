
# ChatBot

A chatbot built with Rasa. The chatbot is designed to handle conversations and provide responses based on predefined intents and actions.


## Deployment

To run this project 

```bash
  git clone https://github.com/BibekRai44/ChatBot
```
```
  pip install -r requirements.txt
```
```
  cd ChatBot
```
let actions running  in first terminal 
```
  rasa run actions
```
run below line in second terminal
```
  rasa train && rasa shell --debug
```
# Customization

You can customize the chatbot's behavior by modifying the following files:

1) data/nlu.yml: Define the training data for the chatbot's NLU (Natural Language Understanding) model.

2) data/stories.yml: Define the conversation flow and dialogue management of the chatbot.
3) actions/actions.py: Implement custom actions for the chatbot, such as calling external APIs or performing specific tasks.
4) domain.yml: Define the chatbot's domain, including intents, entities, actions, and responses.

Make sure to retrain the chatbot (rasa train) after making any changes to these files.
