# Chatbot-Google-Dialogflow
A bot made using **Google Dialogflow** for **iNeuron.ai** (an EdTech startup) for course related queries and consultancies.

## Introduction

A **chatbot** is an AI software application that mimics conversation with a human in natural languages through various platforms like messaging, websites, mobiles etc. The chatbot responds by identifying the intent of the conversation and then responding accordingly. **Dialogflow** is a natural language understanding platform that makes it easy to design and integrate a conversational user interface into your mobile app, web application, device, bot, interactive voice response system, and so on.

## The problem statement:

**To build a chatbot(named iNeuron) which can answer all the queries of a customer and whenever a customer does an enquiry, it automatically send the customer the course details. Also an email is sent to the support team to assist the customer futher with their queries.**

It uses **Python** and **Dialogflow** framework to analyse the user's message, classify it into the a broader category and then reply with a suitable message or the required information. It is hosted using **flask** and is available on **heroku** at the link specified above.

## Application Architecture:

![image](https://user-images.githubusercontent.com/91668225/186893338-aa101741-1ea0-4381-93de-ed62a9741bef.png)

## Flow:

a)	The end-user types or speaks an expression.

b)	Dialogflow matches the end-user expression to an intent and extracts parameters.

c)	Dialogflow sends a **webhook** request message to your webhook service. This message contains information about the matched intent, the action, the parameters, and the response defined for the intent.

d)	Your service performs actions as needed, like database queries or external API calls.

e)	Your service sends a webhook response message to Dialogflow. This message contains the response that should be sent to the end-user.

f)	Dialogflow sends the response to the end-user.

g)	The end-user sees or hears the response.

### Functionalities achived in fulfilment:

a)	Sending an email to the customer with the syllabus and all the course details based on the course selected.

b)	Sending an email to the Support team to further contact the customer for further clarification.

## Installation :

* pip install requirements.txt

* Enable Webhook of Google Dialogflow and Test Its Working

* FAQ - Frequently Asked Quetions Are Given By Orgnization 

* MIME - Multipurpose Internet Mail Extensions (MIME) MIME is an Internet standard that extends the format of email messages to support text in character sets other than ASCII, as well as attachments of audio, video, images, and application programs.

* Make Sure About The Context that You Will Add in Dialogflow / Chatbot , it should be always be related to user's query.


