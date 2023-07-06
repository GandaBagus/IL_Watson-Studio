# Create a Chatbot experience to help students learning remotely to find courses and develop curriculums

<br>
<p align="center">
  <img src="GIFs/Assistant.gif"  width=400 height="800">
</p>
<br>

## Pattern
https://developer.ibm.com/patterns/chatbot-for-student-self-service-in-education/

## Description
In the era of ever-evolving digital transformation, the interaction between users and websites has become important and has become one of the key aspects of providing a satisfying experience. To increase interaction and provide more efficient service. Many companies and organizations have adopted chatbot technology as an innovative solution.
Online New Student Admission (PPDB), as a platform used by students who wish to enroll in their  school, provides information about new student registration and online registration services. To improve convenience in the process of registering new students, a new feature was created, namely a chatbot that uses services from IBM Cloud, namely the Watson Assistant. Watson Assistant is a service from IBM powered by powerful artificial intelligence, which enables the building of intelligent and responsive chatbots. By utilizing Watson Assistant as a chatbot, it is hoped that the registration process and the information needed by students can be fulfilled.
The SiPens chatbot created using the Watson Assistant service has the ability to naturally understand user questions and requests. Using natural language processing and machine learning, these chatbots can provide accurate and relevant responses.





## Flow

<img src="./Foto/Arsitektur.png" alt="Architecture" /> 

- User sends messages to the application (running locally or on IBM Cloud).
- The application sends the user message to IBM Watson Assistant service, and displays the ongoing chat in a web page.


## Included components

* [IBM Watson Assistant](https://www.ibm.com/cloud/watson-assistant/): Build, test and deploy a bot or virtual agent across mobile devices, messaging platforms, or even on a physical robot.


## Pre-requsites

* [IBM Cloud Account](https://cloud.ibm.com/).
* Basic familiarity of [IBM Cloud](https://cloud.ibm.com/), [Assistant service](https://cloud.ibm.com/docs/assistant?topic=assistant-getting-started), [Natural Language Understanding (NLU) service](https://cloud.ibm.com/docs/services/natural-language-understanding?topic=natural-language-understanding-getting-started#getting-started) and [Discovery service](https://cloud.ibm.com/docs/discovery?topic=discovery-getting-started).

## Steps

Follow these steps to setup and run this code pattern. The steps are described in detail below.


1. [Create IBM Cloud services](#2-create-ibm-cloud-services)


2. [Configure Watson Assistant and Test the Chatbot](#5-configure-watson-assistant-and-test-the-chatbot)


## 1. Create IBM Cloud services

Create the following services:

* [**Watson Assistant**](https://cloud.ibm.com/catalog/services/assistant) 


> **NOTE**: use the `Plus` offering of Watson Assistant. You have access to a 30 day trial.



## 2. Configure Watson Assistant and test the Chatbot

### Create assistant

* Find the Assistant service in your IBM Cloud Dashboard.

* Click on the service and then click on `Launch Watson Assistant`.

* Go to your Assistant tab and click `create assistant`. 











### Chatbot ini dibuat menggunakan 

* [![watson][watson]][watson]

### Link
[SiPenS BOT](https://gandabagus.github.io/bot/)


  [watson]: https://img.shields.io/badge/watson-assistant-blue
