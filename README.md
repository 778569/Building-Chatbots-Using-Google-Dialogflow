# Building-Chatbots-Using-Google-Dialogflow
This Repo is about an AI-powered tool for creating text-based conversational interfaces for various business applications. Instructor Lee Assam demonstrates its use case, introducing key features and concepts, and demonstrating how to configure and deploy chatbots on a website using Dialogflow's platform-specific integration options.

## Learning objectives
* Dialogflow building blocks
* Setting up a Dialogflow account
* Creating intents
* Importing and exporting an agent
* Creating entities and parameters
* Adding follow-up intents
* Input and output context
* Creating a fulfillment
* Integrating a chatbot with your website


## Dialogflow

* Need google account.
* Enterprise edition- Not free
* Standerd edition - most featurtes are free. but do not go over quota limit.
* Dialogflow involves mostly configuration via a user interface.
* Google dialog flow continuouslt updates dialogflow user interface.
* Screen may have been updated

## Natural Language Understanding(NLU)

* NLU translate human language into computer language and vice versa
* Very similar to Natural Language processing(NLP) but entails more.
* NLU detects errors, spelling mistakes and sentiment and it incorm
* NLU works with voice and text thought of as ML.
* Machine Learning helps to drive NLU.


## What is Dialogflow?

* leverages NLU to build conversational interfaces
* NLU engine processes and understands what your users are looking for

### Architecture 

![agents-dialogflow](https://github.com/778569/Building-Chatbots-Using-Google-Dialogflow/assets/52319671/84c0e454-3977-43f8-b9f5-e207b1a76c42)

<br><br>
dialog flow sit in the middlebr
Users interface with it in a multitude of channels including apps, messengers, voice and smart home devices.
Dialog flow translate natural language into machine readable data using ML model that are tained by examples that you provide.
Ones understanding waht users are requesting it can hand off to your backend services and APIs. which can then makes things happen to service the users request.
you can call an API, query or insert a record into a database and integrate with third party tools like your CRM system.
Summary - Dialogflow simplifies the process of building conversational experiences for ChatBox.

### Pizza Chatbot

1. Building a pizza chatbot
2. Take pizza orders
3. Get details such as size, ingredients, toppings and crust
4. Getcustomer contact information

# Steps

## Intents
* Agent will house intents and other components. (Parent of our chat bot)
* Also have one major intents. - OrderPizzaIntent
* This intent of the responcible for collection information about a pizza order.

## Entites and Parameters

* Custome entities this included entitiy types like - (Pizza size, ingredients, Crust Type)

## Context and follow-up Intents

* Input and output context will be created
* Have to go one part of the convercation to another
* Follow-up intents created fro conversational flow.

## Fulfillment

* Use fulfi;;ment to calculate the cost of the order.
* Power of Natural language Understanding and some help of ML










